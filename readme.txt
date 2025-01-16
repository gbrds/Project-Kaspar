CREATE TABLE products (
  id INT UNSIGNED NOT NULL AUTO_INCREMENT,
  title VARCHAR(255) NOT NULL,
  price DOUBLE NOT NULL,
  description TEXT NOT NULL,
  imageURL VARCHAR(255) NOT NULL,
  PRIMARY KEY (id)
);


insert into products (title, price, description, imageURL) values ('Book1', '19.99', 'NY best seller', ''), ('Book2', '29.99', 'NY second best seller', '');