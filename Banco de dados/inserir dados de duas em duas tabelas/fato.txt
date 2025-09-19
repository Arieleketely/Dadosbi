DECLARE @i INT = 1;
WHILE @i <= 50
BEGIN
    INSERT INTO Fato (id_doenca, id_hospital, id_medicamento, id_pessoa, id_plano)
    VALUES (@i, @i, @i, @i, @i);
    
    SET @i = @i + 1;
END;