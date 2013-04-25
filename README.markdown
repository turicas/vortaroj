# `vortaroj` - a Python dict that speaks many languages

![vortaroj logo](vortaroj-logo.png)


One of the reasons Python is a great programming language is the availability
of high level data structures, such as
[lists](http://docs.python.org/2/tutorial/datastructures.html#more-on-lists),
[tuples](http://docs.python.org/2/tutorial/datastructures.html#tuples-and-sequences),
[sets](http://docs.python.org/2/tutorial/datastructures.html#sets) and
[dictionaries](http://docs.python.org/2/tutorial/datastructures.html#dictionaries).

In special, pythonistas are _hash addicted_: they like dictionaries and use it
a lot. But sometimes, having an in-memory dict is not sufficient: we want it
persistent or acessible through other machines. Solutions for this kind of
problem are available, like [Memcache](http://www.memcached.org/),
[MemcacheDB](http://memcachedb.org/), [Riak](http://basho.com/riak/),
[Redis](http://redis.io/) and other key-value databases (actually, sometimes
we use NoSQL and even relational databases for this job). However, generally
the interface is changed, so we need to change for the dead simple Python dict
interface to something different/weird.

[vortaroj](https://github.com/turicas/vortaroj) came to solve this problem: it
has a `dict`-like interface to many backends; it's like an ORM to key-value
databases.


## Why the name "vortaroj"?

"Vortaroj" means "dictionaries" in
[Esperanto](http://en.wikipedia.org/wiki/Esperanto) - a language created not to
be the first language of somebody, but to be the second language of everyone.

The original name was "vortaro" but as the domain vortaro.org was taken by
somebody else, [@andrebco](https://github.com/andrebco) suggested the plural
"vortaroj".


## License

[vortaroj](https://github.com/turicas/vortaroj) is licensed under
[GNU General Public License version 3](https://www.gnu.org/licenses/gpl-3.0.html).


## Related Links

- <https://github.com/disqus/durabledict>
- <https://github.com/reclosedev/requests-cache>
