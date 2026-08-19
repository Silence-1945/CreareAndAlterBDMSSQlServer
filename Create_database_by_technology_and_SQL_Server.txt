CREATE DATABASE technic;

USE technic;

CREATE TABLE laptop(
    cod INT IDENTITY PRIMARY KEY,
    model VARCHAR(30) NOT NULL,
    cpu VARCHAR(30) NOT NULL,
    gpu VARCHAR(30) NOT NULL,
    ram VARCHAR(30) NOT NULL
    );
CREATE TABLE ps(
    cod INT IDENTITY PRIMARY KEY,
    cpu VARCHAR(30) NOT NULL,
    gpu VARCHAR(30) NOT NULL,
    ram VARCHAR(30) NOT NULL
    );
