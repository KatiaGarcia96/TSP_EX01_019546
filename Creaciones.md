-- TSP_EX01_019546

--City
CREATE TABLE EX1_019546.City_table
(
  id_city         INTEGER,
  name_city       VARCHAR2(500),
  state_province  VARCHAR2(500),
  country_name    VARCHAR2(500),
  zip_code        VARCHAR2(500)
);


ALTER TABLE EX1_019546.City_table ADD (
  CONSTRAINT City_table_PK
  PRIMARY KEY
  (id_city)
  ENABLE VALIDATE);

