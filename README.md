# ASL2ENG
American Sign Language to English Using OpenCV, Tensorflow, Google Colaboratoy, Anaconda Data Science


## নির্মাণ পর্ব

  ০.  Specifications: Windows 10 Home Single Language x64Bit. 12GB RAM Intel i3 8Gen 8130U CPU @2.20GHz 

  ১.  Install Anaconda Data Science Platform Version 2021.4 or any version that supports minimum python 3.7
  
  ২.  Install Microsoft Visual Studio Community 2017 version (Desktop Development with C++)
  
  ৩.  Download https://github.com/protocolbuffers/protobuf/releases/download/v3.15.8/protoc-3.15.8-win64.zip & Extract it in System(C:), Create A new folder (I named as "Additional packages"). Then create a new "User Variable Path" under the "Environment Variables" section in Advanced System Settings. Paste The directiory bin location (C:\Additional Packages\protoc\bin) & save 
  
  ৪.  Install Git for clone Git Repository & GPU if needed
  
  ৫.  Clone The Repository of Tensorflow by typing in Command Prompt/Powershell or Windows Terminal by typing  git clone https://github.com/tensorflow/models into any directory where you want to install & train your Tensorflow Object Detection API. Source models & Versions are available in Tensorflow's documentation. For My purpose I used in (H:)
  
  ৬.  Open Command Prompt in that Directory for my case H:> & then type the command for copy files models\research>copy object_detection\packages\tf2\setup.py .
  
  ৭.  After copy of that file then install all the requirements of tensorflow object deteection api by typing  \models\research>python -m pip install .
  
  ৮.  Wait for download. This is quite a lengthy process.
  
  ৯. After installing all files, Enviroment is ready for testing

## TEST RUN

Before Installion Anaconda 2021.4 pip list

  alabaster                          0.7.12
  anaconda-client                    1.7.2
  anaconda-navigator                 2.0.3
  anaconda-project                   0.9.1
  anyio                              2.2.0
  appdirs                            1.4.4
  argh                               0.26.2
  argon2-cffi                        20.1.0
  asn1crypto                         1.4.0
  astroid                            2.5
  astropy                            4.2.1
  async-generator                    1.10
  atomicwrites                       1.4.0
  attrs                              20.3.0
  autopep8                           1.5.6
  Babel                              2.9.0
  backcall                           0.2.0
  backports.functools-lru-cache      1.6.4
  backports.shutil-get-terminal-size 1.0.0
  backports.tempfile                 1.0
  backports.weakref                  1.0.post1
  bcrypt                             3.2.0
  beautifulsoup4                     4.9.3
  bitarray                           1.9.2
  bkcharts                           0.2
  black                              19.10b0
  bleach                             3.3.0
  bokeh                              2.3.1
  boto                               2.49.0
  Bottleneck                         1.3.2
  brotlipy                           0.7.0
  certifi                            2020.12.5
  cffi                               1.14.5
  chardet                            4.0.0
  click                              7.1.2
  cloudpickle                        1.6.0
  clyent                             1.2.2
  colorama                           0.4.4
  comtypes                           1.1.9
  conda                              4.10.1
  conda-build                        3.21.4
  conda-content-trust                0+unknown
  conda-package-handling             1.7.3
  conda-repo-cli                     1.0.4
  conda-token                        0.3.0
  conda-verify                       3.4.2
  contextlib2                        0.6.0.post1
  cryptography                       3.4.7
  cycler                             0.10.0
  Cython                             0.29.23
  cytoolz                            0.11.0
  dask                               2021.4.0
  decorator                          5.0.6
  defusedxml                         0.7.1
  diff-match-patch                   20200713
  distributed                        2021.4.0
  docutils                           0.17
  entrypoints                        0.3
  et-xmlfile                         1.0.1
  fastcache                          1.1.0
  filelock                           3.0.12
  flake8                             3.9.0
  Flask                              1.1.2
  fsspec                             0.9.0
  future                             0.18.2
  gevent                             21.1.2
  glob2                              0.7
  greenlet                           1.0.0
  h5py                               2.10.0
  HeapDict                           1.0.1
  html5lib                           1.1
  idna                               2.10
  imagecodecs                        2021.3.31
  imageio                            2.9.0
  imagesize                          1.2.0
  importlib-metadata                 3.10.0
  iniconfig                          1.1.1
  intervaltree                       3.1.0
  ipykernel                          5.3.4
  ipython                            7.22.0
  ipython-genutils                   0.2.0
  ipywidgets                         7.6.3
  isort                              5.8.0
  itsdangerous                       1.1.0
  jdcal                              1.4.1
  jedi                               0.17.2
  Jinja2                             2.11.3
  joblib                             1.0.1
  json5                              0.9.5
  jsonschema                         3.2.0
  jupyter                            1.0.0
  jupyter-client                     6.1.12
  jupyter-console                    6.4.0
  jupyter-core                       4.7.1
  jupyter-packaging                  0.7.12
  jupyter-server                     1.4.1
  jupyterlab                         3.0.14
  jupyterlab-pygments                0.1.2
  jupyterlab-server                  2.4.0
  jupyterlab-widgets                 1.0.0
  keyring                            22.3.0
  kiwisolver                         1.3.1
  lazy-object-proxy                  1.6.0
  libarchive-c                       2.9
  llvmlite                           0.36.0
  locket                             0.2.1
  lxml                               4.6.3
  MarkupSafe                         1.1.1
  matplotlib                         3.3.4
  mccabe                             0.6.1
  menuinst                           1.4.16
  mistune                            0.8.4
  mkl-fft                            1.3.0
  mkl-random                         1.2.1
  mkl-service                        2.3.0
  mock                               4.0.3
  more-itertools                     8.7.0
  mpmath                             1.2.1
  msgpack                            1.0.2
  multipledispatch                   0.6.0
  mypy-extensions                    0.4.3
  navigator-updater                  0.2.1
  nbclassic                          0.2.6
  nbclient                           0.5.3
  nbconvert                          6.0.7
  nbformat                           5.1.3
  nest-asyncio                       1.5.1
  networkx                           2.5
  nltk                               3.6.1
  nose                               1.3.7
  notebook                           6.3.0
  numexpr                            2.7.3
  numpy                              1.20.1
  numpydoc                           1.1.0
  olefile                            0.46
  openpyxl                           3.0.7
  packaging                          20.9
  pandas                             1.2.4
  pandocfilters                      1.4.3
  paramiko                           2.7.2
  parso                              0.7.0
  partd                              1.2.0
  path                               15.1.2
  pathlib2                           2.3.5
  pathspec                           0.7.0
  patsy                              0.5.1
  pep8                               1.7.1
  pexpect                            4.8.0
  pickleshare                        0.7.5
  Pillow                             8.2.0
  pip                                21.0.1
  pkginfo                            1.7.0
  pluggy                             0.13.1
  ply                                3.11
  prometheus-client                  0.10.1
  prompt-toolkit                     3.0.17
  psutil                             5.8.0
  ptyprocess                         0.7.0
  py                                 1.10.0
  pycodestyle                        2.6.0
  pycosat                            0.6.3
  pycparser                          2.20
  pycurl                             7.43.0.6
  pydocstyle                         6.0.0
  pyerfa                             1.7.3
  pyflakes                           2.2.0
  Pygments                           2.8.1
  pylint                             2.7.4
  pyls-black                         0.4.6
  pyls-spyder                        0.3.2
  PyNaCl                             1.4.0
  pyodbc                             4.0.0-unsupported
  pyOpenSSL                          20.0.1
  pyparsing                          2.4.7
  pyreadline                         2.1
  pyrsistent                         0.17.3
  PySocks                            1.7.1
  pytest                             6.2.3
  python-dateutil                    2.8.1
  python-jsonrpc-server              0.4.0
  python-language-server             0.36.2
  pytz                               2021.1
  PyWavelets                         1.1.1
  pywin32                            227
  pywin32-ctypes                     0.2.0
  pywinpty                           0.5.7
  PyYAML                             5.4.1
  pyzmq                              20.0.0
  QDarkStyle                         2.8.1
  QtAwesome                          1.0.2
  qtconsole                          5.0.3
  QtPy                               1.9.0
  regex                              2021.4.4
  requests                           2.25.1
  rope                               0.18.0
  Rtree                              0.9.7
  ruamel-yaml-conda                  0.15.100
  scikit-image                       0.18.1
  scikit-learn                       0.24.1
  scipy                              1.6.2
  seaborn                            0.11.1
  Send2Trash                         1.5.0
  setuptools                         52.0.0.post20210125
  simplegeneric                      0.8.1
  singledispatch                     0.0.0
  sip                                4.19.13
  six                                1.15.0
  sniffio                            1.2.0
  snowballstemmer                    2.1.0
  sortedcollections                  2.1.0
  sortedcontainers                   2.3.0
  soupsieve                          2.2.1
  Sphinx                             3.5.3
  sphinxcontrib-applehelp            1.0.2
  sphinxcontrib-devhelp              1.0.2
  sphinxcontrib-htmlhelp             1.0.3
  sphinxcontrib-jsmath               1.0.1
  sphinxcontrib-qthelp               1.0.3
  sphinxcontrib-serializinghtml      1.1.4
  sphinxcontrib-websupport           1.2.4
  spyder                             4.2.5
  spyder-kernels                     1.10.2
  SQLAlchemy                         1.4.7
  statsmodels                        0.12.2
  sympy                              1.8
  tables                             3.6.1
  tblib                              1.7.0
  terminado                          0.9.4
  testpath                           0.4.4
  textdistance                       4.2.1
  threadpoolctl                      2.1.0
  three-merge                        0.1.1
  tifffile                           2021.4.8
  toml                               0.10.2
  toolz                              0.11.1
  tornado                            6.1
  tqdm                               4.59.0
  traitlets                          5.0.5
  typed-ast                          1.4.2
  typing-extensions                  3.7.4.3
  ujson                              4.0.2
  unicodecsv                         0.14.1
  urllib3                            1.26.4
  watchdog                           1.0.2
  wcwidth                            0.2.5
  webencodings                       0.5.1
  Werkzeug                           1.0.1
  wheel                              0.36.2
  widgetsnbextension                 3.5.1
  win-inet-pton                      1.1.0
  win-unicode-console                0.5
  wincertstore                       0.2
  wrapt                              1.12.1
  xlrd                               2.0.1
  XlsxWriter                         1.3.8
  xlwings                            0.23.0
  xlwt                               1.3.0
  xmltodict                          0.12.0
  yapf                               0.31.0
  zict                               2.0.0
  zipp                               3.4.1
  zope.event                         4.5.0
  zope.interface                     5.3.0



After Install

Processing h:\models\research
Collecting avro-python3
  Downloading avro-python3-1.10.2.tar.gz (38 kB)
Collecting apache-beam
  Downloading apache_beam-2.37.0-cp38-cp38-win_amd64.whl (4.1 MB)
     |████████████████████████████████| 4.1 MB 299 kB/s
Requirement already satisfied: pillow in c:\users\user\anaconda3\lib\site-packages (from object-detection==0.1) (8.2.0)
Requirement already satisfied: lxml in c:\users\user\anaconda3\lib\site-packages (from object-detection==0.1) (4.6.3)
Requirement already satisfied: matplotlib in c:\users\user\anaconda3\lib\site-packages (from object-detection==0.1) (3.3.4)
Requirement already satisfied: Cython in c:\users\user\anaconda3\lib\site-packages (from object-detection==0.1) (0.29.23)
Requirement already satisfied: contextlib2 in c:\users\user\anaconda3\lib\site-packages (from object-detection==0.1) (0.6.0.post1)
Collecting tf-slim
  Downloading tf_slim-1.1.0-py2.py3-none-any.whl (352 kB)
     |████████████████████████████████| 352 kB 2.2 MB/s
Requirement already satisfied: six in c:\users\user\anaconda3\lib\site-packages (from object-detection==0.1) (1.15.0)
Collecting pycocotools
  Downloading pycocotools-2.0.4.tar.gz (106 kB)
     |████████████████████████████████| 106 kB 6.4 MB/s
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
    Preparing wheel metadata ... done
Collecting lvis
  Downloading lvis-0.5.3-py3-none-any.whl (14 kB)
Requirement already satisfied: scipy in c:\users\user\anaconda3\lib\site-packages (from object-detection==0.1) (1.6.2)
Requirement already satisfied: pandas in c:\users\user\anaconda3\lib\site-packages (from object-detection==0.1) (1.2.4)
Collecting tf-models-official>=2.5.1
  Downloading tf_models_official-2.8.0-py2.py3-none-any.whl (2.2 MB)
     |████████████████████████████████| 2.2 MB 1.6 MB/s
Collecting tensorflow_io
  Downloading tensorflow_io-0.24.0-cp38-cp38-win_amd64.whl (21.8 MB)
     |████████████████████████████████| 21.8 MB 819 kB/s
Collecting keras
  Downloading keras-2.8.0-py2.py3-none-any.whl (1.4 MB)
     |████████████████████████████████| 1.4 MB 939 kB/s
Collecting py-cpuinfo>=3.3.0
  Downloading py-cpuinfo-8.0.0.tar.gz (99 kB)
     |████████████████████████████████| 99 kB 930 kB/s
Collecting tensorflow-datasets
  Downloading tensorflow_datasets-4.5.2-py3-none-any.whl (4.2 MB)
     |████████████████████████████████| 4.2 MB 503 kB/s
Collecting tensorflow~=2.8.0
  Downloading tensorflow-2.8.0-cp38-cp38-win_amd64.whl (438.0 MB)
     |████████████████████████████████| 438.0 MB 15 kB/s
Collecting sentencepiece
  Downloading sentencepiece-0.1.96-cp38-cp38-win_amd64.whl (1.1 MB)
     |████████████████████████████████| 1.1 MB 3.3 MB/s
Collecting oauth2client
  Downloading oauth2client-4.1.3-py2.py3-none-any.whl (98 kB)
     |████████████████████████████████| 98 kB 886 kB/s
Collecting tensorflow-addons
  Downloading tensorflow_addons-0.16.1-cp38-cp38-win_amd64.whl (755 kB)
     |████████████████████████████████| 755 kB 1.7 MB/s
Requirement already satisfied: numpy>=1.15.4 in c:\users\user\anaconda3\lib\site-packages (from tf-models-official>=2.5.1->object-detection==0.1) (1.20.1)
Collecting sacrebleu
  Downloading sacrebleu-2.0.0-py3-none-any.whl (90 kB)
     |████████████████████████████████| 90 kB 1.4 MB/s
Collecting kaggle>=1.3.9
  Downloading kaggle-1.5.12.tar.gz (58 kB)
     |████████████████████████████████| 58 kB 901 kB/s
Collecting seqeval
  Downloading seqeval-1.2.2.tar.gz (43 kB)
     |████████████████████████████████| 43 kB 159 kB/s
Collecting tensorflow-text~=2.8.0
  Downloading tensorflow_text-2.8.1-cp38-cp38-win_amd64.whl (2.5 MB)
     |████████████████████████████████| 2.5 MB 930 kB/s
Collecting gin-config
  Downloading gin_config-0.5.0-py3-none-any.whl (61 kB)
     |████████████████████████████████| 61 kB 967 kB/s
Collecting tensorflow-model-optimization>=0.4.1
  Downloading tensorflow_model_optimization-0.7.2-py2.py3-none-any.whl (237 kB)
     |████████████████████████████████| 237 kB 1.7 MB/s
Collecting tensorflow-hub>=0.6.0
  Downloading tensorflow_hub-0.12.0-py2.py3-none-any.whl (108 kB)
     |████████████████████████████████| 108 kB 2.2 MB/s
Requirement already satisfied: pyyaml<6.0,>=5.1 in c:\users\user\anaconda3\lib\site-packages (from tf-models-official>=2.5.1->object-detection==0.1) (5.4.1)
Requirement already satisfied: psutil>=5.4.3 in c:\users\user\anaconda3\lib\site-packages (from tf-models-official>=2.5.1->object-detection==0.1) (5.8.0)
Collecting opencv-python-headless
  Downloading opencv_python_headless-4.5.5.64-cp36-abi3-win_amd64.whl (35.3 MB)
     |████████████████████████████████| 35.3 MB 819 kB/s
Collecting google-api-python-client>=1.6.7
  Downloading google_api_python_client-2.42.0-py2.py3-none-any.whl (8.3 MB)
     |████████████████████████████████| 8.3 MB 819 kB/s
Collecting uritemplate<5,>=3.0.1
  Downloading uritemplate-4.1.1-py2.py3-none-any.whl (10 kB)
Collecting google-auth-httplib2>=0.1.0
  Downloading google_auth_httplib2-0.1.0-py2.py3-none-any.whl (9.3 kB)
Collecting google-api-core!=2.0.*,!=2.1.*,!=2.2.*,!=2.3.0,<3.0.0dev,>=1.31.5
  Downloading google_api_core-2.7.1-py3-none-any.whl (114 kB)
     |████████████████████████████████| 114 kB 3.3 MB/s
Collecting httplib2<1dev,>=0.15.0
  Downloading httplib2-0.20.4-py3-none-any.whl (96 kB)
     |████████████████████████████████| 96 kB 323 kB/s
Collecting google-auth<3.0.0dev,>=1.16.0
  Downloading google_auth-2.6.2-py2.py3-none-any.whl (156 kB)
     |████████████████████████████████| 156 kB 2.2 MB/s
Collecting protobuf>=3.12.0
  Downloading protobuf-3.19.4-cp38-cp38-win_amd64.whl (895 kB)
     |████████████████████████████████| 895 kB 2.2 MB/s
Requirement already satisfied: requests<3.0.0dev,>=2.18.0 in c:\users\user\anaconda3\lib\site-packages (from google-api-core!=2.0.*,!=2.1.*,!=2.2.*,!=2.3.0,<3.0.0dev,>=1.31.5->google-api-python-client>=1.6.7->tf-models-official>=2.5.1->object-detection==0.1) (2.25.1)
Collecting googleapis-common-protos<2.0dev,>=1.52.0
  Downloading googleapis_common_protos-1.56.0-py2.py3-none-any.whl (241 kB)
     |████████████████████████████████| 241 kB 1.1 MB/s
Collecting rsa<5,>=3.1.4
  Downloading rsa-4.8-py3-none-any.whl (39 kB)
Collecting pyasn1-modules>=0.2.1
  Downloading pyasn1_modules-0.2.8-py2.py3-none-any.whl (155 kB)
     |████████████████████████████████| 155 kB 726 kB/s
Collecting cachetools<6.0,>=2.0.0
  Downloading cachetools-5.0.0-py3-none-any.whl (9.1 kB)
Requirement already satisfied: pyparsing!=3.0.0,!=3.0.1,!=3.0.2,!=3.0.3,<4,>=2.4.2 in c:\users\user\anaconda3\lib\site-packages (from httplib2<1dev,>=0.15.0->google-api-python-client>=1.6.7->tf-models-official>=2.5.1->object-detection==0.1) (2.4.7)
Requirement already satisfied: certifi in c:\users\user\anaconda3\lib\site-packages (from kaggle>=1.3.9->tf-models-official>=2.5.1->object-detection==0.1) (2020.12.5)
Requirement already satisfied: python-dateutil in c:\users\user\anaconda3\lib\site-packages (from kaggle>=1.3.9->tf-models-official>=2.5.1->object-detection==0.1) (2.8.1)
Requirement already satisfied: tqdm in c:\users\user\anaconda3\lib\site-packages (from kaggle>=1.3.9->tf-models-official>=2.5.1->object-detection==0.1) (4.59.0)
Collecting python-slugify
  Downloading python_slugify-6.1.1-py2.py3-none-any.whl (9.1 kB)
Requirement already satisfied: urllib3 in c:\users\user\anaconda3\lib\site-packages (from kaggle>=1.3.9->tf-models-official>=2.5.1->object-detection==0.1) (1.26.4)
Requirement already satisfied: pytz>=2017.3 in c:\users\user\anaconda3\lib\site-packages (from pandas->object-detection==0.1) (2021.1)
Collecting pyasn1<0.5.0,>=0.4.6
  Downloading pyasn1-0.4.8-py2.py3-none-any.whl (77 kB)
     |████████████████████████████████| 77 kB 275 kB/s
Requirement already satisfied: idna<3,>=2.5 in c:\users\user\anaconda3\lib\site-packages (from requests<3.0.0dev,>=2.18.0->google-api-core!=2.0.*,!=2.1.*,!=2.2.*,!=2.3.0,<3.0.0dev,>=1.31.5->google-api-python-client>=1.6.7->tf-models-official>=2.5.1->object-detection==0.1) (2.10)
Requirement already satisfied: chardet<5,>=3.0.2 in c:\users\user\anaconda3\lib\site-packages (from requests<3.0.0dev,>=2.18.0->google-api-core!=2.0.*,!=2.1.*,!=2.2.*,!=2.3.0,<3.0.0dev,>=1.31.5->google-api-python-client>=1.6.7->tf-models-official>=2.5.1->object-detection==0.1) (4.0.0)
Collecting tf-estimator-nightly==2.8.0.dev2021122109
  Downloading tf_estimator_nightly-2.8.0.dev2021122109-py2.py3-none-any.whl (462 kB)
     |████████████████████████████████| 462 kB 939 kB/s
Collecting astunparse>=1.6.0
  Downloading astunparse-1.6.3-py2.py3-none-any.whl (12 kB)
Collecting gast>=0.2.1
  Downloading gast-0.5.3-py3-none-any.whl (19 kB)
Requirement already satisfied: wrapt>=1.11.0 in c:\users\user\anaconda3\lib\site-packages (from tensorflow~=2.8.0->tf-models-official>=2.5.1->object-detection==0.1) (1.12.1)
Collecting libclang>=9.0.1
  Downloading libclang-13.0.0-py2.py3-none-win_amd64.whl (13.9 MB)
     |████████████████████████████████| 13.9 MB 34 kB/s
Requirement already satisfied: setuptools in c:\users\user\anaconda3\lib\site-packages (from tensorflow~=2.8.0->tf-models-official>=2.5.1->object-detection==0.1) (52.0.0.post20210125)
Requirement already satisfied: typing-extensions>=3.6.6 in c:\users\user\anaconda3\lib\site-packages (from tensorflow~=2.8.0->tf-models-official>=2.5.1->object-detection==0.1) (3.7.4.3)
Collecting absl-py>=0.4.0
  Downloading absl_py-1.0.0-py3-none-any.whl (126 kB)
     |████████████████████████████████| 126 kB 29 kB/s
Collecting opt-einsum>=2.3.2
  Downloading opt_einsum-3.3.0-py3-none-any.whl (65 kB)
     |████████████████████████████████| 65 kB 51 kB/s
Collecting grpcio<2.0,>=1.24.3
  Downloading grpcio-1.45.0-cp38-cp38-win_amd64.whl (3.5 MB)
     |████████████████████████████████| 3.5 MB 6.3 kB/s
Collecting flatbuffers>=1.12
  Downloading flatbuffers-2.0-py2.py3-none-any.whl (26 kB)
Collecting termcolor>=1.1.0
  Downloading termcolor-1.1.0.tar.gz (3.9 kB)
Requirement already satisfied: h5py>=2.9.0 in c:\users\user\anaconda3\lib\site-packages (from tensorflow~=2.8.0->tf-models-official>=2.5.1->object-detection==0.1) (2.10.0)
Collecting tensorflow-io-gcs-filesystem>=0.23.1
  Downloading tensorflow_io_gcs_filesystem-0.24.0-cp38-cp38-win_amd64.whl (1.5 MB)
     |████████████████████████████████| 1.5 MB 1.1 MB/s
Collecting tensorboard<2.9,>=2.8
  Downloading tensorboard-2.8.0-py3-none-any.whl (5.8 MB)
     |████████████████████████████████| 5.8 MB 819 kB/s
Collecting keras-preprocessing>=1.1.1
  Downloading Keras_Preprocessing-1.1.2-py2.py3-none-any.whl (42 kB)
     |████████████████████████████████| 42 kB 225 kB/s
Collecting google-pasta>=0.1.1
  Downloading google_pasta-0.2.0-py3-none-any.whl (57 kB)
     |████████████████████████████████| 57 kB 166 kB/s
Requirement already satisfied: wheel<1.0,>=0.23.0 in c:\users\user\anaconda3\lib\site-packages (from astunparse>=1.6.0->tensorflow~=2.8.0->tf-models-official>=2.5.1->object-detection==0.1) (0.36.2)
Collecting markdown>=2.6.8
  Downloading Markdown-3.3.6-py3-none-any.whl (97 kB)
     |████████████████████████████████| 97 kB 762 kB/s
Collecting google-auth-oauthlib<0.5,>=0.4.1
  Downloading google_auth_oauthlib-0.4.6-py2.py3-none-any.whl (18 kB)
Requirement already satisfied: werkzeug>=0.11.15 in c:\users\user\anaconda3\lib\site-packages (from tensorboard<2.9,>=2.8->tensorflow~=2.8.0->tf-models-official>=2.5.1->object-detection==0.1) (1.0.1)
Collecting tensorboard-plugin-wit>=1.6.0
  Downloading tensorboard_plugin_wit-1.8.1-py3-none-any.whl (781 kB)
     |████████████████████████████████| 781 kB 1.7 MB/s
Collecting tensorboard-data-server<0.7.0,>=0.6.0
  Downloading tensorboard_data_server-0.6.1-py3-none-any.whl (2.4 kB)
Collecting requests-oauthlib>=0.7.0
  Downloading requests_oauthlib-1.3.1-py2.py3-none-any.whl (23 kB)
Collecting importlib-metadata>=4.4
  Downloading importlib_metadata-4.11.3-py3-none-any.whl (18 kB)
Requirement already satisfied: zipp>=0.5 in c:\users\user\anaconda3\lib\site-packages (from importlib-metadata>=4.4->markdown>=2.6.8->tensorboard<2.9,>=2.8->tensorflow~=2.8.0->tf-models-official>=2.5.1->object-detection==0.1) (3.4.1)
Collecting oauthlib>=3.0.0
  Downloading oauthlib-3.2.0-py3-none-any.whl (151 kB)
     |████████████████████████████████| 151 kB 2.2 MB/s
Collecting dm-tree~=0.1.1
  Downloading dm_tree-0.1.6-cp38-cp38-win_amd64.whl (75 kB)
     |████████████████████████████████| 75 kB 646 kB/s
Collecting proto-plus<2,>=1.7.1
  Downloading proto_plus-1.20.3-py3-none-any.whl (46 kB)
     |████████████████████████████████| 46 kB 418 kB/s
Collecting pymongo<4.0.0,>=3.8.0
  Downloading pymongo-3.12.3-cp38-cp38-win_amd64.whl (398 kB)
     |████████████████████████████████| 398 kB 1.3 MB/s
Collecting pydot<2,>=1.2.0
  Downloading pydot-1.4.2-py2.py3-none-any.whl (21 kB)
Collecting orjson<4.0
  Downloading orjson-3.6.7-cp38-none-win_amd64.whl (186 kB)
     |████████████████████████████████| 186 kB 1.6 MB/s
Collecting hdfs<3.0.0,>=2.1.0
  Downloading hdfs-2.6.0-py3-none-any.whl (33 kB)
Collecting dill<0.3.2,>=0.3.1.1
  Downloading dill-0.3.1.1.tar.gz (151 kB)
     |████████████████████████████████| 151 kB 1.7 MB/s
Collecting pyarrow<7.0.0,>=0.15.1
  Downloading pyarrow-6.0.1-cp38-cp38-win_amd64.whl (15.5 MB)
     |████████████████████████████████| 15.5 MB 160 kB/s
Collecting httplib2<1dev,>=0.15.0
  Downloading httplib2-0.19.1-py3-none-any.whl (95 kB)
     |████████████████████████████████| 95 kB 777 kB/s
Collecting fastavro<2,>=0.23.6
  Downloading fastavro-1.4.10-cp38-cp38-win_amd64.whl (416 kB)
     |████████████████████████████████| 416 kB 1.7 MB/s
Collecting cloudpickle<3,>=2.0.0
  Downloading cloudpickle-2.0.0-py3-none-any.whl (25 kB)
Collecting crcmod<2.0,>=1.7
  Downloading crcmod-1.7.tar.gz (89 kB)
     |████████████████████████████████| 89 kB 883 kB/s
Collecting docopt
  Downloading docopt-0.6.2.tar.gz (25 kB)
Collecting opencv-python>=4.1.0.25
  Downloading opencv_python-4.5.5.64-cp36-abi3-win_amd64.whl (35.4 MB)
     |████████████████████████████████| 35.4 MB 386 kB/s
Requirement already satisfied: cycler>=0.10.0 in c:\users\user\anaconda3\lib\site-packages (from lvis->object-detection==0.1) (0.10.0)
Requirement already satisfied: kiwisolver>=1.1.0 in c:\users\user\anaconda3\lib\site-packages (from lvis->object-detection==0.1) (1.3.1)
Collecting text-unidecode>=1.3
  Downloading text_unidecode-1.3-py2.py3-none-any.whl (78 kB)
     |████████████████████████████████| 78 kB 244 kB/s
Requirement already satisfied: regex in c:\users\user\anaconda3\lib\site-packages (from sacrebleu->tf-models-official>=2.5.1->object-detection==0.1) (2021.4.4)
Requirement already satisfied: colorama in c:\users\user\anaconda3\lib\site-packages (from sacrebleu->tf-models-official>=2.5.1->object-detection==0.1) (0.4.4)
Collecting tabulate>=0.8.9
  Downloading tabulate-0.8.9-py3-none-any.whl (25 kB)
Collecting portalocker
  Downloading portalocker-2.4.0-py2.py3-none-any.whl (16 kB)
Requirement already satisfied: pywin32>=226 in c:\users\user\anaconda3\lib\site-packages (from portalocker->sacrebleu->tf-models-official>=2.5.1->object-detection==0.1) (227)
Requirement already satisfied: scikit-learn>=0.21.3 in c:\users\user\anaconda3\lib\site-packages (from seqeval->tf-models-official>=2.5.1->object-detection==0.1) (0.24.1)
Requirement already satisfied: joblib>=0.11 in c:\users\user\anaconda3\lib\site-packages (from scikit-learn>=0.21.3->seqeval->tf-models-official>=2.5.1->object-detection==0.1) (1.0.1)
Requirement already satisfied: threadpoolctl>=2.0.0 in c:\users\user\anaconda3\lib\site-packages (from scikit-learn>=0.21.3->seqeval->tf-models-official>=2.5.1->object-detection==0.1) (2.1.0)
Collecting typeguard>=2.7
  Downloading typeguard-2.13.3-py3-none-any.whl (17 kB)
Collecting promise
  Downloading promise-2.3.tar.gz (19 kB)
Collecting tensorflow-metadata
  Downloading tensorflow_metadata-1.7.0-py3-none-any.whl (48 kB)
     |████████████████████████████████| 48 kB 908 kB/s
Collecting importlib-resources
  Downloading importlib_resources-5.4.0-py3-none-any.whl (28 kB)
Building wheels for collected packages: object-detection, kaggle, py-cpuinfo, termcolor, crcmod, dill, avro-python3, docopt, pycocotools, seqeval, promise
  Building wheel for object-detection (setup.py) ... done
  Created wheel for object-detection: filename=object_detection-0.1-py3-none-any.whl size=1698309 sha256=fee3a6db36437d1aedbaa70ab7bb9be7b84130e4535264f45fb1aed206f6e3be
  Stored in directory: C:\Users\User\AppData\Local\Temp\pip-ephem-wheel-cache-ubotoea5\wheels\51\bc\a0\723f9f2f00a033799daaf1eabe18ea3f8ab725620b6d261b4d
  Building wheel for kaggle (setup.py) ... done
  Created wheel for kaggle: filename=kaggle-1.5.12-py3-none-any.whl size=73053 sha256=b10d06ad47bd4b14106059018e124770722101c2952515cf5914c502e520f5c4
  Stored in directory: c:\users\user\appdata\local\pip\cache\wheels\29\da\11\144cc25aebdaeb4931b231e25fd34b394e6a5725cbb2f50106
  Building wheel for py-cpuinfo (setup.py) ... done
  Created wheel for py-cpuinfo: filename=py_cpuinfo-8.0.0-py3-none-any.whl size=22245 sha256=720906c238d97382962180fdf14d07fe91a77a30c37a5078e8329eb2b89f86f8
  Stored in directory: c:\users\user\appdata\local\pip\cache\wheels\57\cb\6d\bab2257f26c5be4a96ff65c3d2a7122c96529b73773ee37f36
  Building wheel for termcolor (setup.py) ... done
  Created wheel for termcolor: filename=termcolor-1.1.0-py3-none-any.whl size=4829 sha256=6c7c4d0d98af9aeeefa86d8061940deba6769cae2203ec398505111886f63e42
  Stored in directory: c:\users\user\appdata\local\pip\cache\wheels\a0\16\9c\5473df82468f958445479c59e784896fa24f4a5fc024b0f501
  Building wheel for crcmod (setup.py) ... done
  Created wheel for crcmod: filename=crcmod-1.7-cp38-cp38-win_amd64.whl size=25214 sha256=e9a74859216d0b19e6a8baa0f57ef697e71fa81ae99c88359302b8b404858c46
  Stored in directory: c:\users\user\appdata\local\pip\cache\wheels\ca\5a\02\f3acf982a026f3319fb3e798a8dca2d48fafee7761788562e9
  Building wheel for dill (setup.py) ... done
  Created wheel for dill: filename=dill-0.3.1.1-py3-none-any.whl size=78594 sha256=8bd5890dd7e1ffd0619acd28c3c88f3143c008da009a73dc3172ac044bb7e461
  Stored in directory: c:\users\user\appdata\local\pip\cache\wheels\07\35\78\e9004fa30578734db7f10e7a211605f3f0778d2bdde38a239d
  Building wheel for avro-python3 (setup.py) ... done
  Created wheel for avro-python3: filename=avro_python3-1.10.2-py3-none-any.whl size=44009 sha256=11304fe437dccdd50b2249fac077ed77a1af4c11d571f31362772397d6fd004c
  Stored in directory: c:\users\user\appdata\local\pip\cache\wheels\bb\73\e9\d273421f5723c4bf544dcf9eb097bda94421ef8d3252699f0a
  Building wheel for docopt (setup.py) ... done
  Created wheel for docopt: filename=docopt-0.6.2-py2.py3-none-any.whl size=13705 sha256=c053d611751a56e6bb3de5eb7f31de991aab53097d29fbfce2ef665281413e03
  Stored in directory: c:\users\user\appdata\local\pip\cache\wheels\56\ea\58\ead137b087d9e326852a851351d1debf4ada529b6ac0ec4e8c
  Building wheel for pycocotools (PEP 517) ... done
  Created wheel for pycocotools: filename=pycocotools-2.0.4-cp38-cp38-win_amd64.whl size=73018 sha256=ab0057ddf5ee873a9c860ebb0ccd34281f7db2b20e03f26c94af23e80eb5c07a
  Stored in directory: c:\users\user\appdata\local\pip\cache\wheels\dd\e2\43\3e93cd653b3346b3d702bb0509bc611189f95d60407bff1484
  Building wheel for seqeval (setup.py) ... done
  Created wheel for seqeval: filename=seqeval-1.2.2-py3-none-any.whl size=16170 sha256=98d519531a635885bee7d7793b7927f9f8f4a60030d5fedc8b4dba3bcd56ed53
  Stored in directory: c:\users\user\appdata\local\pip\cache\wheels\ad\5c\ba\05fa33fa5855777b7d686e843ec07452f22a66a138e290e732
  Building wheel for promise (setup.py) ... done
  Created wheel for promise: filename=promise-2.3-py3-none-any.whl size=21494 sha256=c664b44e6d7094bd4ff5056c1ae69563b6d2f5611381a105ed8e94a12da587fb
  Stored in directory: c:\users\user\appdata\local\pip\cache\wheels\54\aa\01\724885182f93150035a2a91bce34a12877e8067a97baaf5dc8
Successfully built object-detection kaggle py-cpuinfo termcolor crcmod dill avro-python3 docopt pycocotools seqeval promise
Installing collected packages: pyasn1, rsa, pyasn1-modules, oauthlib, cachetools, requests-oauthlib, importlib-metadata, google-auth, tensorboard-plugin-wit, tensorboard-data-server, protobuf, markdown, grpcio, google-auth-oauthlib, absl-py, tf-estimator-nightly, text-unidecode, termcolor, tensorflow-io-gcs-filesystem, tensorboard, opt-einsum, libclang, keras-preprocessing, keras, httplib2, googleapis-common-protos, google-pasta, gast, flatbuffers, astunparse, uritemplate, typeguard, tensorflow-metadata, tensorflow-hub, tensorflow, tabulate, python-slugify, promise, portalocker, importlib-resources, google-auth-httplib2, google-api-core, docopt, dm-tree, dill, tf-slim, tensorflow-text, tensorflow-model-optimization, tensorflow-datasets, tensorflow-addons, seqeval, sentencepiece, sacrebleu, pymongo, pydot, pycocotools, pyarrow, py-cpuinfo, proto-plus, orjson, opencv-python-headless, opencv-python, oauth2client, kaggle, hdfs, google-api-python-client, gin-config, fastavro, crcmod, cloudpickle, tf-models-official, tensorflow-io, lvis, avro-python3, apache-beam, object-detection
  Attempting uninstall: importlib-metadata
    Found existing installation: importlib-metadata 3.10.0
    Uninstalling importlib-metadata-3.10.0:
      Successfully uninstalled importlib-metadata-3.10.0
  Attempting uninstall: cloudpickle
    Found existing installation: cloudpickle 1.6.0
    Uninstalling cloudpickle-1.6.0:
      Successfully uninstalled cloudpickle-1.6.0
      Successfully installed absl-py-1.0.0 apache-beam-2.37.0 astunparse-1.6.3 avro-python3-1.10.2 cachetools-5.0.0 cloudpickle-2.0.0 crcmod-1.7 dill-0.3.1.1 dm-tree-0.1.6 docopt-0.6.2 fastavro-1.4.10 flatbuffers-2.0 gast-0.5.3 gin-config-0.5.0 google-api-core-2.7.1 google-api-python-client-2.42.0 google-auth-2.6.2 google-auth-httplib2-0.1.0 google-auth-oauthlib-0.4.6 google-pasta-0.2.0 googleapis-common-protos-1.56.0 grpcio-1.45.0 hdfs-2.6.0 httplib2-0.19.1 importlib-metadata-4.11.3 importlib-resources-5.4.0 kaggle-1.5.12 keras-2.8.0 keras-preprocessing-1.1.2 libclang-13.0.0 lvis-0.5.3 markdown-3.3.6 oauth2client-4.1.3 oauthlib-3.2.0 object-detection-0.1 opencv-python-4.5.5.64 opencv-python-headless-4.5.5.64 opt-einsum-3.3.0 orjson-3.6.7 portalocker-2.4.0 promise-2.3 proto-plus-1.20.3 protobuf-3.19.4 py-cpuinfo-8.0.0 pyarrow-6.0.1 pyasn1-0.4.8 pyasn1-modules-0.2.8 pycocotools-2.0.4 pydot-1.4.2 pymongo-3.12.3 python-slugify-6.1.1 requests-oauthlib-1.3.1 rsa-4.8 sacrebleu-2.0.0 sentencepiece-0.1.96 seqeval-1.2.2 tabulate-0.8.9 tensorboard-2.8.0 tensorboard-data-server-0.6.1 tensorboard-plugin-wit-1.8.1 tensorflow-2.8.0 tensorflow-addons-0.16.1 tensorflow-datasets-4.5.2 tensorflow-hub-0.12.0 tensorflow-io-0.24.0 tensorflow-io-gcs-filesystem-0.24.0 tensorflow-metadata-1.7.0 tensorflow-model-optimization-0.7.2 tensorflow-text-2.8.1 termcolor-1.1.0 text-unidecode-1.3 tf-estimator-nightly-2.8.0.dev2021122109 tf-models-official-2.8.0 tf-slim-1.1.0 typeguard-2.13.3 uritemplate-4.1.1 


Copyright 2018-2022 rafsan
