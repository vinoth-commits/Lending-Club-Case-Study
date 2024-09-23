# Project Name
> Lending Club Project case study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.

      As the largest online loan marketplace, the company specializes in facilitating personal, business, and medical loans.
      Borrowers can conveniently obtain lower interest loans through a streamlined online interface.

- What is the background of your project?

      Lending loans to risky applicants is the largest source of financial loss.
      Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed.
      Identification of such applicants using exploratory data analysis (EDA) is the aim of this case study.


- What is the business probem that your project is trying to solve?

      The study focuses on identifying factors that may contribute to loan applicants defaulting on their payments. 
      The company wants to understand the driving factors behind loan default.  i.e. the variables which are strong indicators of default.  
      The company can utilise this knowledge for its portfolio and risk assessment. 

- What is the dataset that is being used?

      loan.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Conclusion 1: 

  Summary of Univariate Analysis:

      1. Applicants with rented homes accounted for the highest defaults (50%).

      2. Debt consolidation loans led to the most defaults (49%).

      3. Borrowers with an interest rate between 11% to 17% had the highest default rate.

      4. Loans in the amount range of 5000 to 10000 were most prone to default.

- Conclusion 2:

  Summary of Derived Metrics:

      1. Type-driven Metric: Applicants with 10+ years of experience account for 28% of defaults, the highest among experience groups.

      2. Business-driven Metric: Loans issued in December have the highest default rate.
      
      3. Data-driven Metrics:

            Applicants with an annual income between 30,000 and 60,000 defaulted the most.
            
            Interestingly, those in the lower income range (1,000 to 30,000) showed fewer defaults.
            
            Borrowers with a monthly debt-to-income ratio of 10% to 20% had the highest default rate.

- Conclusion 3:

  Summary of Bivariate Analysis:

      1. Annual Income vs Loan Purpose: The highest default rates are seen in loans for credit cards, small businesses, home improvement, and house mortgages.

      2. Annual Income vs Debt-to-Income (DTI) Ratio: Borrowers with incomes between 30000 and 70000 and a DTI ratio between 15% and 25% show debt management issues.

      3. Loan Amount vs Annual Income: A moderate positive correlation (0.41) indicates that as annual income increases, the loan amount tends to rise as well.

      4. Loan Amount vs Grade: High default rates are observed when the loan grade is F or G and the loan amount exceeds 17000.

- Conclusion 4:

  Summary of Multivariate Analysis: 

      1. Small business loans show a high rate of default.

      2. Credit card and debt consolidation loans are at a significant risk of default, with many borrowers on the verge of defaulting.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
-     Package                           Version
--------------------------------- ------------
*	aext-assistant                    4.0.15
*	aext-assistant-server             4.0.15
*	aext-core                         4.0.15
*	aext-core-server                  4.0.15
*	aext-panels                       4.0.15
*	aext-panels-server                4.0.15
*	aext-share-notebook               4.0.15
*	aext-share-notebook-server        4.0.15
*	aext-shared                       4.0.15
*	aiobotocore                       2.7.0
*	aiohttp                           3.9.3
*	aioitertools                      0.7.1
*	aiosignal                         1.2.0
*	alabaster                         0.7.12
*	altair                            5.0.1
*	anaconda-anon-usage               0.4.3
*	anaconda-catalogs                 0.2.0
*	anaconda-client                   1.12.3
*	anaconda-cloud-auth               0.5.1
*	anaconda-navigator                2.6.2
*	anaconda-project                  0.11.1
*	anyio                             4.2.0
*	appdirs                           1.4.4
*	applaunchservices                 0.3.0
*	appnope                           0.1.2
*	appscript                         1.1.2
*	archspec                          0.2.3
*	argon2-cffi                       21.3.0
*	argon2-cffi-bindings              21.2.0
*	arrow                             1.2.3
*	astroid                           2.14.2
*	astropy                           5.3.4
*	asttokens                         2.0.5
*	async-lru                         2.0.4
*	atomicwrites                      1.4.0
*	attrs                             23.1.0
*	Automat                           20.2.0
*	autopep8                          1.6.0
*	Babel                             2.11.0
*	backports.functools-lru-cache     1.6.4
*	backports.tempfile                1.0
*	backports.weakref                 1.0.post1
*	bcrypt                            3.2.0
*	beautifulsoup4                    4.12.2
*	binaryornot                       0.4.4
*	black                             23.11.0
*	bleach                            4.1.0
*	blinker                           1.6.2
*	bokeh                             3.3.4
*	boltons                           23.0.0
*	botocore                          1.31.64
*	Bottleneck                        1.3.7
*	Brotli                            1.0.9
*	cachetools                        4.2.2
*	certifi                           2024.8.30
*	cffi                              1.16.0
*	chardet                           4.0.0
*	charset-normalizer                2.0.4
*	click                             8.1.7
*	cloudpickle                       2.2.1
*	clyent                            1.2.2
*	colorama                          0.4.6
*	colorcet                          3.0.1
*	comm                              0.1.2
*	conda                             24.7.1
*	conda-build                       24.1.2
*	conda-content-trust               0.2.0
*	conda_index                       0.4.0
*	conda-libmamba-solver             24.1.0
*	conda-pack                        0.6.0
*	conda-package-handling            2.2.0
*	conda_package_streaming           0.9.0
*	conda-repo-cli                    1.0.75
*	conda-token                       0.4.0
*	conda-verify                      3.4.2
*	constantly                        23.10.4
*	contourpy                         1.2.0
*	cookiecutter                      2.5.0
*	cryptography                      42.0.2
*	cssselect                         1.2.0
*	cycler                            0.11.0
*	cytoolz                           0.12.2
*	dask                              2023.11.0
*	datashader                        0.16.0
*	debugpy                           1.6.7
*	decorator                         5.1.1
*	defusedxml                        0.7.1
*	diff-match-patch                  20200713
*	dill                              0.3.7
*	distributed                       2023.11.0
*	distro                            1.8.0
*	dmglib                            0.9.5
*	docstring-to-markdown             0.11
*	docutils                          0.18.1
*	entrypoints                       0.4
*	et-xmlfile                        1.1.0
*	executing                         0.8.3
*	fastjsonschema                    2.16.2
*	filelock                          3.13.1
*	flake8                            6.0.0
*	Flask                             2.2.5
*	fonttools                         4.25.0
*	frozendict                        2.4.2
*	frozenlist                        1.4.0
*	fsspec                            2023.10.0
*	future                            0.18.3
*	gensim                            4.3.0
*	gitdb                             4.0.7
*	GitPython                         3.1.37
*	gmpy2                             2.1.2
*	greenlet                          3.0.1
*	h11                               0.14.0
*	h5py                              3.9.0
*	HeapDict                          1.0.1
*	holoviews                         1.18.3
*	httpcore                          1.0.2
*	httpx                             0.26.0
*	hvplot                            0.9.2
*	hyperlink                         21.0.0
*	idna                              3.4
*	imagecodecs                       2023.1.23
*	imageio                           2.33.1
*	imagesize                         1.4.1
*	imbalanced-learn                  0.11.0
*	importlib-metadata                7.0.1
*	incremental                       22.10.0
*	inflection                        0.5.1
*	iniconfig                         1.1.1
*	intake                            0.6.8
*	intervaltree                      3.1.0
*	ipykernel                         6.28.0
*	ipython                           8.20.0
*	ipython-genutils                  0.2.0
*	ipywidgets                        7.6.5
*	isort                             5.9.3
*	itemadapter                       0.3.0
*	itemloaders                       1.1.0
*	itsdangerous                      2.0.1
*	jaraco.classes                    3.2.1
*	jedi                              0.18.1
*	jellyfish                         1.0.1
*	Jinja2                            3.1.3
*	jmespath                          1.0.1
*	joblib                            1.2.0
*	json5                             0.9.6
*	jsonpatch                         1.32
*	jsonpointer                       2.1
*	jsonschema                        4.19.2
*	jsonschema-specifications         2023.7.1
*	jupyter                           1.0.0
*	jupyter_client                    8.6.0
*	jupyter-console                   6.6.3
*	jupyter_core                      5.5.0
*	jupyter-events                    0.8.0
*	jupyter-lsp                       2.2.0
*	jupyter_server                    2.10.0
*	jupyter_server_terminals          0.4.4
*	jupyterlab                        4.0.11
*	jupyterlab-pygments               0.1.2
*	jupyterlab_server                 2.25.1
*	jupyterlab-widgets                3.0.9
*	keyring                           23.13.1
*	kiwisolver                        1.4.4
*	lazy_loader                       0.3
*	lazy-object-proxy                 1.6.0
*	lckr_jupyterlab_variableinspector 3.1.0
*	libarchive-c                      2.9
*	libmambapy                        1.5.6
*	linkify-it-py                     2.0.0
*	llvmlite                          0.42.0
*	lmdb                              1.4.1
*	locket                            1.0.0
*	lxml                              4.9.3
*	lz4                               4.3.2
*	Markdown                          3.4.1
*	markdown-it-py                    2.2.0
*	MarkupSafe                        2.1.3
*	matplotlib                        3.8.0
*	matplotlib-inline                 0.1.6
*	mccabe                            0.7.0
*	mdit-py-plugins                   0.3.0
*	mdurl                             0.1.0
*	menuinst                          2.0.2
*	mistune                           2.0.4
*	more-itertools                    10.1.0
*	mpmath                            1.3.0
*	msgpack                           1.0.3
*	multidict                         6.0.4
*	multipledispatch                  0.6.0
*	munkres                           1.1.4
*	mypy                              1.8.0
*	mypy-extensions                   1.0.0
*	navigator-updater                 0.4.0
*	nbclient                          0.8.0
*	nbconvert                         7.10.0
*	nbformat                          5.9.2
*	nest-asyncio                      1.6.0
*	networkx                          3.1
*	nltk                              3.8.1
*	notebook                          7.0.8
*	notebook_shim                     0.2.3
*	numba                             0.59.0
*	numexpr                           2.8.7
*	numpy                             1.26.4
*	numpydoc                          1.5.0
*	openpyxl                          3.0.10
*	overrides                         7.4.0
*	packaging                         23.1
*	pandas                            2.1.4
*	pandocfilters                     1.5.0
*	panel                             1.3.8
*	param                             2.0.2
*	parsel                            1.8.1
*	parso                             0.8.3
*	partd                             1.4.1
*	pathlib                           1.0.1
*	pathspec                          0.10.3
*	patsy                             0.5.3
*	pexpect                           4.8.0
*	pickleshare                       0.7.5
*	pillow                            10.2.0
*	pip                               23.3.1
*	pkce                              1.0.3
*	pkginfo                           1.9.6
*	platformdirs                      3.10.0
*	plotly                            5.9.0
*	pluggy                            1.0.0
*	ply                               3.11
*	prometheus-client                 0.14.1
*	prompt-toolkit                    3.0.43
*	Protego                           0.1.16
*	protobuf                          3.20.3
*	psutil                            5.9.0
*	ptyprocess                        0.7.0
*	pure-eval                         0.2.2
*	py-cpuinfo                        9.0.0
*	pyarrow                           14.0.2
*	pyasn1                            0.4.8
*	pyasn1-modules                    0.2.8
*	pycodestyle                       2.10.0
*	pycosat                           0.6.6
*	pycparser                         2.21
*	pyct                              0.5.0
*	pycurl                            7.45.2
*	pydantic                          1.10.12
*	pydeck                            0.8.0
*	PyDispatcher                      2.0.5
*	pydocstyle                        6.3.0
*	pyerfa                            2.0.0
*	pyflakes                          3.0.1
*	Pygments                          2.15.1
*	PyJWT                             2.4.0
*	pylint                            2.16.2
*	pylint-venv                       2.3.0
*	pyls-spyder                       0.4.0
*	pyobjc-core                       9.0
*	pyobjc-framework-Cocoa            9.0
*	pyobjc-framework-CoreServices     9.0
*	pyobjc-framework-FSEvents         9.0
*	pyodbc                            5.0.1
*	pyOpenSSL                         24.0.0
*	pyparsing                         3.0.9
*	PyQt5                             5.15.10
*	PyQt5-sip                         12.13.0
*	PyQtWebEngine                     5.15.6
*	PySocks                           1.7.1
*	pytest                            7.4.0
*	python-dateutil                   2.8.2
*	python-dotenv                     0.21.0
*	python-json-logger                2.0.7
*	python-lsp-black                  1.2.1
*	python-lsp-jsonrpc                1.0.0
*	python-lsp-server                 1.7.2
*	python-slugify                    5.0.2
*	python-snappy                     0.6.1
*	pytoolconfig                      1.2.6
*	pytz                              2023.3.post1
*	pyviz_comms                       3.0.0
*	pywavelets                        1.5.0
*	PyYAML                            6.0.1
*	pyzmq                             25.1.2
*	QDarkStyle                        3.0.2
*	qstylizer                         0.2.2
*	QtAwesome                         1.2.2
*	qtconsole                         5.4.2
*	QtPy                              2.4.1
*	queuelib                          1.6.2
*	referencing                       0.30.2
*	regex                             2023.10.3
*	requests                          2.31.0
*	requests-file                     1.5.1
*	requests-toolbelt                 1.0.0
*	rfc3339-validator                 0.1.4
*	rfc3986-validator                 0.1.1
*	rich                              13.3.5
*	rope                              1.7.0
*	rpds-py                           0.10.6
*	Rtree                             1.0.1
*	ruamel.yaml                       0.17.21
*	ruamel-yaml-conda                 0.17.21
*	s3fs                              2023.10.0
*	scikit-image                      0.22.0
*	scikit-learn                      1.2.2
*	scipy                             1.11.4
*	Scrapy                            2.8.0
*	seaborn                           0.12.2
*	semver                            2.13.0
*	Send2Trash                        1.8.2
*	service-identity                  18.1.0
*	setuptools                        68.2.2
*	sip                               6.7.12
*	six                               1.16.0
*	smart-open                        5.2.1
*	smmap                             4.0.0
*	sniffio                           1.3.0
*	snowballstemmer                   2.2.0
*	sortedcontainers                  2.4.0
*	soupsieve                         2.5
*	Sphinx                            5.0.2
*	sphinxcontrib-applehelp           1.0.2
*	sphinxcontrib-devhelp             1.0.2
*	sphinxcontrib-htmlhelp            2.0.0
*	sphinxcontrib-jsmath              1.0.1
*	sphinxcontrib-qthelp              1.0.3
*	sphinxcontrib-serializinghtml     1.1.5
*	spyder                            5.4.3
*	spyder-kernels                    2.4.4
*	SQLAlchemy                        2.0.25
*	stack-data                        0.2.0
*	statsmodels                       0.14.0
*	streamlit                         1.30.0
*	sympy                             1.12
*	tables                            3.9.2
*	tabulate                          0.9.0
*	tblib                             1.7.0
*	tenacity                          8.2.2
*	terminado                         0.17.1
*	text-unidecode                    1.3
*	textdistance                      4.2.1
*	threadpoolctl                     2.2.0
*	three-merge                       0.1.1
*	tifffile                          2023.4.12
*	tinycss2                          1.2.1
*	tldextract                        3.2.0
*	toml                              0.10.2
*	tomlkit                           0.11.1
*	toolz                             0.12.0
*	tornado                           6.3.3
*	tqdm                              4.65.0
*	traitlets                         5.7.1
*	truststore                        0.8.0
*	Twisted                           23.10.0
*	typing_extensions                 4.9.0
*	tzdata                            2023.3
*	tzlocal                           2.1
*	uc-micro-py                       1.0.1
*	ujson                             5.4.0
*	Unidecode                         1.2.0
*	urllib3                           2.0.7
*	validators                        0.18.2
*	w3lib                             2.1.2
*	watchdog                          2.1.6
*	wcwidth                           0.2.5
*	webencodings                      0.5.1
*	websocket-client                  0.58.0
*	Werkzeug                          2.2.3
*	whatthepatch                      1.0.2
*	wheel                             0.41.2
*	widgetsnbextension                3.5.2
*	wrapt                             1.14.1
*	wurlitzer                         3.0.2
*	xarray                            2023.6.0
*	xlwings                           0.29.1
*	xyzservices                       2022.9.0
*	yapf                              0.31.0
*	yarl                              1.9.3
*	zict                              3.0.0
*	zipp                              3.17.0
*	zope.interface                    5.4.0
*	zstandard                         0.19.0


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Credit:
Since this is a group project, special thanks go to Vishal for his dedicated contribution and effort.
References:
- https://pandas.pydata.org/
- https://matplotlib.org/
- https://seaborn.pydata.org/


## Contact
Created by [https://github.com/vinoth-commits] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->