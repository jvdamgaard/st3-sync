st3-sync
========

Sublime Text 3 settings sync

## Install

- Open terminal

```
cd ~/Library/Application\ Support/Sublime\ Text\ 3//Packages/
rm -r user
mkdir user && cd user
git clone git@github.com:jvdamgaard/st3-sync.git .
```

- Open Sublime Text 3
- Open console
- Copy and paste

```
import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
```
