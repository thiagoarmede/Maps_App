# - Aplicação para salvar geolocalização - Maps_App

Este repositório contém a aplicação RESTful desenvolvida com Node.js com o intuito de praticar as técnicas e tecnologias utilizadas. O app permite que vc entre com latitude e longitude

## SQL do banco gerado

```sql
CREATE DATABASE IF NOT EXISTS `db`;
USE `db` ;

CREATE TABLE IF NOT EXISTS `db`.`places` (
  `id` INT(11) NOT NULL AUTO_INCREMENT,
  `place_id` VARCHAR(30) NULL DEFAULT NULL,
  `address` TEXT NULL DEFAULT NULL,
  `image` TEXT NULL DEFAULT NULL,
  PRIMARY KEY (`id`))
ENGINE = InnoDB
```

Lembre-se de instalar os módulos antes de executar o projeto:
```
npm install
```

E também, não esqueça de colocar a sua key do Google Apis no arquivo index para a aplicação funcionar!!