# MySQL project

> Right now I am making again MySQL project

---

### Creating a table

> After to apply the users table I receive

```

\>CREATE TABLE `devcamp_sql_course_schema`.`new_users` (
  `new_users_id` INT NOT NULL AUTO_INCREMENT,
  `new_users_name` VARCHAR(100) NULL,
  `new_users_email` VARCHAR(80) NOT NULL,
  PRIMARY KEY (`new_users_id`),
  UNIQUE INDEX `new_users_email_UNIQUE` (`new_users_email` ASC) VISIBLE)
\>ENGINE = InnoDB
\>DEFAULT CHARACTER SET = armscii8
\>COMMENT = 'I made this \"new\" tables in the second round seeing the videos.';

```
