-- Создание базы данных
CREATE DATABASE CorrelationDB;

-- Использование созданной базы данных
USE CorrelationDB;

-- Создание таблицы для хранения значений X и Y
CREATE TABLE Data (
    Id INT PRIMARY KEY IDENTITY,
    X FLOAT NOT NULL,
    Y FLOAT NOT NULL
);

-- Создание таблицы для хранения результатов расчета
CREATE TABLE Results (
    Id INT PRIMARY KEY IDENTITY,
    Correlation FLOAT NOT NULL,
    A FLOAT NOT NULL,
    B FLOAT NOT NULL
);

