# The Code 

The program is a virtual ATM machine made in Ruby whit Rspec
testing framework and a fake user and account

The ATM should have funds and every customer should have personal accounts and should only allow withdraws from active accounts.

The customer should be able to withdraw funds of 5, 10 & 20$ bills only if funds are available and the card is valid and if the pin-code is correct.

# Dependencies

* gem RSpec
* gem Pry-byebug
* source 'https://rubygems.org'
* spec_helper
* bundle

# Setup

* To access the virtual ATM machine you need to clone the link below
  https://github.com/FlisAnn/atm_challenge_2020
* To run the code you will need a CLI (Command Line Interface)
* To view the code you will need a text editor

# Instructions

## To use with irb
´´´$ irb
´´´load ‘./lib/account.rb’
´´´load ‘./lib/atm.rb’
´´´load ‘./lib/person.rb’

## Create a user
´´´ann = Person.new(name: ‘Ann’)

## Create account
´´´ann.create_account

## Create ATM
´´´atm = Atm.new
´´´Deposit funds
´´´ann.deposit 100
´´´withdraw funds
´´´ann.withdraw(atm: atm, amount: 50)

# Acknowledgements

* Craft Academy material
* Google
* Stackoverflow
* https://scoutapm.com/blog/how-to-use-lambdas-in-ruby
* Craftoverflow
* Rubygems.org
* https://relishapp.com/rspec/rspec-expectations/v/3-4/docs/built-in-matchers/
* https://www.rubyguides.com/2015/12/ruby-refactoring/

# Updates/Improvments plan
* Build the front end for the virtual ATM.

# License
* MIT License