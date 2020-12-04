This repository contains the code examples from the book [*Elasticsearch in Action*][2].

When do I need them?
--------------------

Because it's nice to have some sample data to run various searches from the
book's listings. Throughout most chapters, there's an example use-case of
running a get-together site, where you have people organizing themselves into
groups and hosting events. Code samples provide you with some data and a script
to index that data.

How do I index the sample data?
-------------------------------

    # clone the repository
    git clone https://github.com/dakrone/elasticsearch-in-action.git

    # switch to a branch that matches your version. Master works with 1.x and 2.x
    # but we currently support 5.x, 6.x and 7.x as well:
    git clone https://github.com/dakrone/elasticsearch-in-action.git -b 7.x

    # index the sample data
    elasticsearch-in-action/populate.sh

I have questions or suggestions for these samples
-------------------------------------------------

You have feedback? We'd be glad to hear it from you on the book's forum. To get there, go to the [live book][1] and click on the discuss button on the top-right. You can also send pull requests or open issues on this repository.

Happy reading and Elasticsearch-ing!

  [1]: https://livebook.manning.com/book/elasticsearch-in-action/
  [2]: http://manning.com/hinman
