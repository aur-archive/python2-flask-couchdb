# Maintainer: Moritz Lipp <mlq@pwmt.org>

_pkgname=Flask-CouchDB
pkgname=python2-flask-couchdb
pkgver=0.2.1
pkgrel=1
pkgdesc="Flask-CouchDB makes it easy to use the powerful CouchDB database with
Flask"
arch=(any)
url="http://packages.python.org/Flask-CouchDB/"
license=('BSD')
depends=('python2' 'python2-flask' 'couchdb')
makedepends=('python2-distribute')
source=("http://pypi.python.org/packages/source/${_pkgname:0:1}/$_pkgname/$_pkgname-$pkgver.tar.gz")
md5sums=('fdfd53150f1a2b053048eb850efebc4d')

package() {
  cd "$srcdir/$_pkgname-$pkgver"
  python2 setup.py install --root="$pkgdir/" --prefix=/usr --optimize=1
}

# vim:set ts=2 sw=2 et:
