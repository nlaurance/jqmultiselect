# Introduction #

ui.multiselect is a jquery extension which can be found here :

`http://www.quasipartikel.at/multiselect/ <http://www.quasipartikel.at/multiselect/>`


# Details #


usage example::

> from tw.forms import TableForm
> from tw.jqmultiselect import Jqmultiselect

> class EditMovieForm(TableForm):
> > submit\_text = 'Edit Movie'


> fields = [
> > Jqmultiselect('actors',
> > > help\_text = 'Please choose the actors of the movie.',
> > > searchable=True, # default = True
> > > sortable=True,   # default=True
> > > ),
> > > ]
