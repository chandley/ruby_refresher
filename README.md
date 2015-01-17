# ruby_refresher

[![Test Coverage](https://codeclimate.com/github/chandley/ruby_refresher/badges/coverage.svg)](https://codeclimate.com/github/chandley/ruby_refresher)
[![Code Climate](https://codeclimate.com/github/chandley/ruby_refresher/badges/gpa.svg)](https://codeclimate.com/github/chandley/ruby_refresher)

## Summary

Ruby refresher - A series of 41 challenges, set as RSpec tests.

### Problem

A series of problems defined by rspec test. They vary in level from quite easy to fairly hard. 

You should be able to answer most questions with a couple of lines of code, and just a few methods. If you're writing a long, complex solution, there's probably a better way.

To run the specs, just run

~~~
$ rspec questions_spec.rb
~~~

**Quick tip**: to run a single example, change `it` to `fit` on that example, then run

~~~
$ rspec questions_spec.rb --tag focus
~~~



### Languages/Platforms/Tools

| Languages | Technologies  | Testing Frameworks| Misc
| :-------------------------------------------- |:--------------|:-----------|:----|
| Ruby      |               | Rspec             |               |
|           |               |                   |               |
|           |               |                   |  
|           |               |


### To do

* One test doesn't pass in Ruby 2.0.0, as the to_h method is not supported by that release.

* A few of the solutions could be tidied up but I'm fairly happy with the current state.

### Learning points

* Ruby file library not so familiar
* There can be a tradeoff between clarity and brevity




