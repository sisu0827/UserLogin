# UserLogin

## Create Database

1. Install and Run Xampp server
2. Create Database name:'erc_token'
3. Create 'user' table:

  ```
  CREATE TABLE IF NOT EXISTS `users` (
  `id` int(5) NOT NULL AUTO_INCREMENT,
  `first_name` text NOT NULL,
  `last_name` text NOT NULL,
  `mob_no` int(11) NOT NULL,
  `user_name` varchar(20) NOT NULL,
  `password` varchar(15) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB  DEFAULT CHARSET=latin1 AUTO_INCREMENT=4 ;
  ```


## How to start development and run tests?

1. Clone this repo.
1. Run `npm install`.
1. Run `node app.js`.
1. Open `localhost:8080` in web browser.
