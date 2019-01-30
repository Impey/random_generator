# random_generator
This application is a baseline random genrator that can be plugged into an api to return a random amount of outputs for the user. Currently the postcode.io API is plugged into the generator

#Language used 
* Ruby

#How to download
1. https://github.com/Impey/random_generator clone the project
2. unzip the project
3. open the project in the code editor

#How to install the gems 
* when in the applications directory in terminal run "bundle install" to install all the needed gems from the gemfile

#How to use 
1. require_relative Generator in order to add the random generator to the project as follows 
```ruby
require_relative '../randomGenerator/Generator'
```
2. To test the generator is working instaniate the generator within your project like so
```ruby
test = Generator.new
test.postcodes 
```
3. Give the generator and arugment in the below example the generator will return 10 values and print the results in terminal
```ruby
 p test.random_array(10)
```










