# The Emacsmirror

The Emacsmirror is a growing collection of [Emacs] Lisp packages.  All
mirrored packages are available as [Git] repositories.  In most cases
this is done by mirroring the upstream Git repository, but if upstream
uses something else, then the mirror nevertheless makes the package
available as a Git repository.

<img src="https://emacsmirror.net/assets/emacsmirror.png">

One primary purpose of the Emacsmirror is to provide a comprehensive
list of available Emacs packages, including packages which have gone
out of fashion (but might later prove to be useful still).

Older efforts attempting to provide a comprehensive list of available
packages, such as the [Emacs Lisp List][ell], over time collected an
impressive list of dead links to packages which were no longer
available anywhere.

With the Emacsmirror this won't happen.  If a package's upstream
disappears, then a copy remains available on the mirror.  Once its
upstream has disappeared a package is usually moved from the
[Emacsmirror] to the [Emacsattic], where it is no longer updated. (The
Emacsattic is a Github "organization" separate from the Emacsmirror
organization, but it is considered part of the Emacsmirror project.)

If other mirrored packages still depend on a package whose upstream
has disappeared or no longer maintains the package, then it is copied
to the [Emacsorphanage].  The Emacsmirror then mirrors that repository
from the orphanage.  The orphanage repository serves as a temporary
home until someone volunteers to take over as maintainer.  While a
package is in the orphanage, the maintainer of the Emacsmirror makes
an effort to merge pull requests from users.

Note that in the past I have sometimes removed packages completely,
instead of moving them to the attic, but going forward that should
only happen in exceptional cases.

*For more information about the Emacsmirror and the `epkg.el` package,
which provides a user interface for browsing the package database,
visit the [Emacsmirror homepage][Emacsmirror]*.

Adding new packages
-------------------

Most packages that are available from Melpa are also available from
the Emacsmirror.  New packages are added to Melpa on a regular basis
and after a short delay these packages are also semi-automatically
added to the Emacsmirror.  So there is no need to ask for new Melpa
additions to be added to the Emacsmirror too.  It will happen but it
might take a few days.

To get a new package added to the mirror add it to Melpa instead.
That way Melpa users benefit too.

Some packages which have been available from Melpa for a long time are
not available from the Emacsmirror.  See [these lists][not-mirror] and
[these pages](/stats) for the various reasons.

<br/><br/>

*Page [CC BY 3.0](https://creativecommons.org/licenses/by/3.0)
by    [Jonas Bernoulli](https://emacsair.me),
image [CC BY-NC-SA 2.0](https://creativecommons.org/licenses/by-nc-sa/2.0)
by    [David Bygott](https://www.flickr.com/photos/davidbygott).*

[Emacsmirror]: https://emacsmirror.net
[not-mirror]:  https://emacsmirror.net/stats/compare.html#orgheadline21
[not-melpa]:   https://emacsmirror.net/stats/compare.html#orgheadline26
