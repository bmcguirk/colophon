# Python Modules
Current List of Python modules installed in my Anaconda distribution. 
Anything with `local` next to it inevitably went through the: 

```bash
$ conda install blah
Using Anaconda Cloud api site https://api.anaconda.org
Fetching package metadata .........
Solving package specifications: .
Error: Package missing in current win-64 channels:
  - blah

You can search for packages on anaconda.org with

    anaconda search -t conda blah
$ conda skeleton pypi blah
$ conda build blah
$ conda install blah --use-local
```
cycle. At some point I'll do annotations and an actual write-up on the true essentials. 

Module          |         Current Version   | Installation Notes
----------------|---------------------------|-------------------
alabaster                 | 0.7.7       |                    py35_0  
anaconda                  | 2.5.0       |        np110py35_0  
anaconda-client           | 1.2.2       |             py35_0  
ansible                   | 2.1.0.0     |              <pip>
argcomplete               | 1.0.0       |             py35_1  
astropy                   | 1.1.1       |        np110py35_0  
babel                     | 2.2.0       |             py35_0  
beautifulsoup4            | 4.4.1       |             py35_0  
bitarray                  | 0.8.1       |             py35_1  
blaze-core                | 0.9.0       |             py35_0  
bokeh                     | 0.11.0      |             py35_0  
boto                      | 2.39.0      |             py35_0  
bottlechest               | 0.7.1       |             py35_0  
bottleneck                | 1.0.0       |        np110py35_0  
bubbles                   | 0.1         |              <pip>
bzip2                     | 1.0.6       |             vc14_2  [vc14]
cffi                      | 1.2.1       |             py35_0  
chardet                   | 2.3.0       |             py35_0  
cloudpickle               | 0.2.1       |             py35_0  
clyent                    | 1.2.0       |             py35_0  
colorama                  | 0.3.6       |             py35_0  
comtypes                  | 1.1.2       |             py35_0  
conda                     | 4.1.11      |             py35_0  
conda-build               | 1.21.4      |             py35_0  
conda-env                 | 2.5.2       |             py35_0  
configobj                 | 5.0.6       |             py35_0  
configparser              | 3.5.0b1     |              <pip>
console_shortcut          | 0.1.1       |             py35_1  
cryptography              | 1.0.2       |             py35_0  
cubes                     | 1.0.1       |             py35_0  
curl                      | 7.45.0      |             vc14_1  [vc14]
cycler                    | 0.9.0       |             py35_0  
cython                    | 0.23.4      |             py35_0  
cytoolz                   | 0.7.5       |             py35_0  
datashape                 | 0.5.0       |             py35_0  
dbf                       | 0.96.003    |             py35_0  
decorator                 | 4.0.6       |             py35_0  
dj-database-url           | 0.4.0       |              <pip>
django                    | 1.9.2       |             py35_0  
django-openbudget         | 0.1.0       |              <pip>
django-tastypie           | 0.13.3      |              <pip>
docutils                  | 0.12        |             py35_1  
dynd-python               | 0.7.1       |             py35_0  
ecdsa                     | 0.11        |              <pip>
ecdsa                     | 0.13        |             py35_0  
et_xmlfile                | 1.0.1       |             py35_0  
ete3                      | 3.0.0b35    |               py_0    etetoolkit
etlTest                   | 0.1.5       |              <pip>
fastcache                 | 1.0.2       |             py35_0  
flask                     | 0.10.1      |             py35_2  
freetype                  | 2.5.5       |             vc14_0  [vc14]
future                    | 0.15.2      |              <pip>
futures                   | 3.0.3       |             py35_0  
greenlet                  | 0.4.9       |             py35_0  
gunicorn                  | 19.4.5      |              <pip>
h5py                      | 2.5.0       |        np110py35_4  
hdf5                      | 1.8.15.1    |             vc14_4  [vc14]
html5lib                  | 0.999       |             py35_0  
idna                      | 2.0         |             py35_0  
ipykernel                 | 4.2.2       |             py35_0  
ipython                   | 4.0.3       |             py35_0  
ipython-notebook          | 4.0.4       |             py35_3  
ipython-qtconsole         | 4.0.1       |             py35_4  
ipython_genutils          | 0.1.0       |             py35_0  
ipywidgets                | 4.1.1       |             py35_0  
itsdangerous              | 0.24        |             py35_0  
jdcal                     | 1.2         |             py35_0  
jedi                      | 0.9.0       |             py35_0  
Jinja2                    | 2.7.3       |              <pip>
jinja2                    | 2.8         |             py35_1  
jpeg                      | 8d          |             vc14_0  [vc14]
jsonschema                | 2.5.1       |             py35_0  
jupyter                   | 1.0.0       |             py35_1  
jupyter_client            | 4.1.1       |             py35_0  
jupyter_console           | 4.1.0       |             py35_0  
jupyter_core              | 4.0.6       |             py35_0  
launcher                  | 1.0.0       |                  4  
libdynd                   | 0.7.1       |                  0  
libpng                    | 1.6.17      |             vc14_1  [vc14]
libsodium                 | 1.0.3       |                  0  
libtiff                   | 4.0.6       |             vc14_1  [vc14]
llvmlite                  | 0.8.0       |             py35_0  
appdirs                   | 1.4.0       |             py35_0    local
blinker                   | 1.4         |             py35_0    local
click                     | 6.6         |             py35_0    local
defusedxml                | 0.3         |             py35_0    local
expressions               | 0.2.2       |             py35_0    local
feedgenerator             | 1.8         |             py35_0    local
fuzzywuzzy                | 0.1         |             py35_0    local
grako                     | 3.9.2       |             py35_0    local
mechanize                 | 0.2.5       |             py35_0    local
oauthlib                  | 1.0.3       |             py35_0    local
pdfrw                     | 0.2         |             py35_0    local
pelican                   | 3.6.3       |             py35_0    local
python-levenshtein        | 0.12.0      |             py35_0    local
requests-oauthlib         | 0.6.1       |             py35_0    local
selenium                  | 2.53.6      |             py35_0    local
spur                      | 0.3.19      |             py35_0    local
spyne                     | 2.12.11     |             py35_0    local
textblob                  | 0.11.1      |             py35_0    local
trello                    | 0.9.1       |             py35_0    local
utils                     | 0.1         |             py35_0    local
lxml                      | 3.6.0       |             py35_0  
markupsafe                | 0.23        |             py35_0  
matplotlib                | 1.5.1       |        np110py35_0  
menuinst                  | 1.3.2       |             py35_0  
mistune                   | 0.7.1       |             py35_0  
mkl                       | 11.3.3      |                  1  
mkl-service               | 1.1.2       |             py35_1  
msvc_runtime              | 1.0.1       |             vc14_0  [vc14]
multipledispatch          | 0.4.8       |             py35_0  
nbconvert                 | 4.1.0       |             py35_0  
nbformat                  | 4.0.1       |             py35_0  
networkx                  | 1.11        |             py35_0  
nltk                      | 3.1         |             py35_0  
node-webkit               | 0.10.1      |                  0  
nose                      | 1.3.7       |             py35_0  
notebook                  | 4.1.0       |             py35_2  
numba                     | 0.23.1      |        np110py35_0  
numexpr                   | 2.6.0       |        np111py35_0  
numpy                     | 1.11.0      |             py35_1  
odo                       | 0.4.0       |             py35_0  
openpyxl                  | 2.3.2       |             py35_0  
openssl                   | 1.0.2g      |             vc14_0  [vc14]
orange-app                | 1.0         |             py35_0  
orange3                   | 3.2a1       |             py35_0  
pandas                    | 0.18.1      |        np111py35_0  
paramiko                  | 1.14.1      |              <pip>
paramiko                  | 1.16.0      |             py35_0  
patch                     | 2.5.9       |                  1  
path.py                   | 8.1.2       |             py35_1  
patsy                     | 0.4.0       |        np110py35_0  
pep8                      | 1.7.0       |             py35_0  
pickleshare               | 0.5         |             py35_0  
pillow                    | 3.2.0       |             py35_1  
pip                       | 8.1.2       |             py35_0  
plac                      | 0.9.6       |             py35_0  
ply                       | 3.8         |             py35_0  
psutil                    | 3.4.2       |             py35_0  
py                        | 1.4.24      |              <pip>
py                        | 1.4.31      |             py35_0  
pyasn1                    | 0.1.9       |             py35_0  
pycosat                   | 0.6.1       |             py35_0  
pycparser                 | 2.14        |             py35_0  
pycrypto                  | 2.6.1       |             py35_3  
pyflakes                  | 1.0.0       |             py35_0  
Pygments                  | 1.6         |              <pip>
pygments                  | 2.1         |             py35_0  
pymongo                   | 3.0.3       |             py35_0  
pyodbc                    | 3.0.10      |             py35_0  
pyopenssl                 | 0.15.1      |             py35_1  
pyparsing                 | 2.0.3       |             py35_0  
pyqt                      | 4.11.4      |             py35_4  
pyqtgraph                 | 0.9.10      |             py35_1  
pyreadline                | 2.1         |             py35_0  
pytables                  | 3.2.2       |        np110py35_1  
pytest                    | 2.8.5       |             py35_0  
python                    | 3.5.1       |                  4  
python-dateutil           | 2.5.3       |             py35_0  
python-mimeparse          | 1.5.1       |              <pip>
pytz                      | 2016.4      |             py35_0  
pywin32                   | 219         |             py35_2  
pyyaml                    | 3.11        |             py35_3  
pyzmq                     | 15.2.0      |             py35_0  
qt                        | 4.8.7       |             vc14_5  [vc14]
qtconsole                 | 4.2.1       |             py35_0  
requests                  | 2.9.1       |             py35_0  
rope                      | 0.9.4       |             py35_1  
ruamel_yaml               | 0.11.7      |             py35_0  
scikit-image              | 0.11.3      |        np110py35_0  
scikit-learn              | 0.17.1      |        np111py35_1  
scipy                     | 0.17.1      |        np111py35_0  
setuptools                | 20.2.2      |             py35_0  
simplegeneric             | 0.8.1       |             py35_0  
sip                       | 4.16.9      |             py35_2  
six                       | 1.10.0      |             py35_0  
snowballstemmer           | 1.2.1       |             py35_0  
sockjs-tornado            | 1.0.1       |             py35_0  
cymem                     | 1.31.2      |        py35_vc14_0  [vc14]  spacy
murmurhash                | 0.26.4      |        py35_vc14_0  [vc14]  spacy
preshed                   | 0.46.4      |        py35_vc14_0  [vc14]  spacy
semver                    | 2.4.1       |             py35_0    spacy
spacy                     | 0.101.0     |        py35_vc14_0  [vc14]  spacy
sputnik                   | 0.9.3       |             py35_0    spacy
thinc                     | 5.0.8       |        py35_vc14_0  [vc14]  spacy
Sphinx                    | 1.2.3       |              <pip>
sphinx                    | 1.3.5       |             py35_0  
sphinx_rtd_theme          | 0.1.9       |             py35_0  
spyder                    | 2.3.8       |             py35_1  
spyder-app                | 2.3.8       |             py35_0  
SQLAlchemy                | 0.9.7       |              <pip>
sqlalchemy                | 1.0.13      |             py35_0  
statsmodels               | 0.6.1       |        np110py35_0  
sympy                     | 0.7.6.1     |             py35_0  
tk                        | 8.5.18      |             vc14_0  [vc14]
toolz                     | 0.7.4       |             py35_0  
tornado                   | 4.3         |             py35_0  
tox                       | 1.7.2       |              <pip>
traitlets                 | 4.1.0       |             py35_0  
twisted                   | 16.2.0      |             py35_0  
unicodecsv                | 0.14.1      |             py35_0  
unidecode                 | 0.04.19     |             py35_0  
vboxapi                   | 1.0         |              <pip>
virtualenv                | 13.0.1      |             py35_0  
vs2015_runtime            | 14.00.23026.0|                 0  
werkzeug                  | 0.11.10     |             py35_0  
wheel                     | 0.29.0      |             py35_0  
xlrd                      | 0.9.4       |             py35_0  
xlsxwriter                | 0.8.4       |             py35_0  
xlwings                   | 0.6.4       |             py35_1  
xlwt                      | 1.0.0       |             py35_0  
zlib                      | 1.2.8       |             vc14_2  [vc14]
zope.interface            | 4.1.3       |             py35_0  
|