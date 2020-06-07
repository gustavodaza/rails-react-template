# Ruby on Rails API and React Initial Configuration

Things you may want to cover:

* Ruby version: 2.7.1

* Rails version: 6.0.3

* React version: 16.13.1

### What it does?

It contains the requirements to run a Rails API and React Client with these third party libraries:

- Axios
- Rspec
- Rubocop
- Eslint
- Http Proxy Middleware

## How Can I Start?

On root folder run

<pre>bundle install && cd client/ && npm install</pre>

To run both servers at the same install

<pre>gem install foreman</pre>

Ruby users should take care *not* to install foreman in their project's `Gemfile`. See this [wiki article](https://github.com/ddollar/foreman/wiki/Don't-Bundle-Foreman) for more details.

then

<pre>foreman start</pre>
