# Ruby Event Store

[![Build Status](https://travis-ci.org/arkency/ruby_event_store.svg?branch=master)](https://travis-ci.org/arkency/ruby_event_store)
[![Gem Version](https://badge.fury.io/rb/ruby_event_store.svg)](http://badge.fury.io/rb/ruby_event_store)
[![Code Climate](https://codeclimate.com/github/arkency/ruby_event_store/badges/gpa.svg)](https://codeclimate.com/github/arkency/ruby_event_store)
[![Test Coverage](https://codeclimate.com/github/arkency/ruby_event_store/badges/coverage.svg)](https://codeclimate.com/github/arkency/ruby_event_store/coverage)

Ruby Event Store is a library for publishing and storing events, which can be further used to build your application state from them.

This can be a solid foundation for a design approach called [_event sourcing_](https://www.youtube.com/watch?v=JHGkaShoyNs). It has [many benefits](http://codebetter.com/gregyoung/2010/02/20/why-use-event-sourcing/) and is an interesting if you happen to struggle with keeping maintainability of your application at a reasonable level.

Ruby Event Store is unopinionated on _how_ events are stored. There is [Rails Event Store](https://github.com/arkency/rails_event_store) library which provides persistence layer suitable for Ruby on Rails.

This documentation serves as a practical guide, as well as a place to describe all basic concepts you need to grasp to benefit from this design choice.
