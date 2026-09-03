# Awesome Python Typing with stars

Collection of awesome Python types, stubs, plugins, and tools to work with them.

## Contents

* [Static type checkers](#static-type-checkers)
* [Dynamic type checkers](#dynamic-type-checkers)
* [Stub packages](#stub-packages)
* [Additional types](#additional-types)
* [Backports and improvements](#backports-and-improvements)
* [Tools](#tools)
* [Integrations](#integrations)
* [Articles](#articles)
* [Related](#related)

[Full list of typed projects on PyPi](https://pypi.org/search/?q=\&o=\&c=Typing+%3A%3A+Typed) is here.

## Static type checkers

* [mypy](https://github.com/python/mypy) ⭐ 20,627 | 🐛 3,226 | 🌐 Python | 📅 2026-09-03 - Optional static typing (PEP 484).
* [ty](https://github.com/astral-sh/ty) ⭐ 19,607 | 🐛 903 | 🌐 Python | 📅 2026-09-03 - An extremely fast Python type checker, written in Rust, from the creators of Ruff and uv.
* [pyright](https://github.com/Microsoft/pyright) ⭐ 15,616 | 🐛 339 | 🌐 Python | 📅 2026-09-02 - Fast type checker meant for large Python source bases. It can run in a “watch” mode and performs fast incremental updates when files are modified.
* [pyrefly](https://github.com/facebook/pyrefly) ⭐ 6,931 | 🐛 703 | 🌐 Rust | 📅 2026-09-03 - A fast type checker and language server for Python.
* [pytype](https://github.com/google/pytype) ⚠️ Archived - Tool to check and infer types - without requiring type annotations.
* [basedpyright](https://github.com/detachhead/basedpyright) ⭐ 3,578 | 🐛 649 | 🌐 TypeScript | 📅 2026-08-21 - Pyright fork with improvements to VSCode support and various other fixes.
* [pylyzer](https://github.com/mtshiba/pylyzer/) ⭐ 2,857 | 🐛 10 | 🌐 Rust | 📅 2025-05-10 - A fast static code analyzer & language server for Python, written in Rust.
* [zuban](https://github.com/zubanls/zuban) ⭐ 1,176 | 🐛 89 | 🌐 Rust | 📅 2026-09-03 - A Mypy-compatible Python type checker and Language Server built in Rust.
* [pyanalyze](https://github.com/quora/pyanalyze) ⭐ 386 | 🐛 61 | 🌐 Python | 📅 2026-01-27 - Extensible static analyzer and type checker.
* [basedmypy](https://github.com/KotlinIsland/basedmypy) ⭐ 200 | 🐛 435 | 🌐 Python | 📅 2025-09-10 - Based static typing with baseline functionality.
* [pycroscope](https://github.com/JelleZijlstra/pycroscope) ⭐ 47 | 🐛 3 | 🌐 Python | 📅 2026-08-29 - A semi-static type checker for Python code. It imports the modules it type checks, enabling `pycroscope` to understand many dynamic constructs that other type checkers will reject. This makes it possible to extend `pycroscope` with plugins that interact directly with your code.
* [PyCharm](https://www.jetbrains.com/pycharm/) - IDE for Professional Developers.

## Dynamic type checkers

* [pydantic](https://github.com/samuelcolvin/pydantic) ⭐ 28,707 | 🐛 576 | 🌐 Python | 📅 2026-09-03 - Data parsing using Python type hinting. Supports dataclasses.
* [beartype](https://github.com/beartype/beartype) ⭐ 3,488 | 🐛 116 | 🌐 Python | 📅 2026-09-03 - Unbearably fast `O(1)` runtime type-checking in pure Python.
* [typeguard](https://github.com/agronholm/typeguard) ⭐ 1,785 | 🐛 43 | 🌐 Python | 📅 2026-08-29 - Another one runtime type checker.
* [pytypes](https://github.com/Stewori/pytypes) ⭐ 203 | 🐛 39 | 🌐 Python | 📅 2023-04-29 - Provides a rich set of utilities for runtime typechecking.
* [typical](https://github.com/seandstewart/typical/) ⚠️ Archived - Data parsing and automatic type-coercion using type hinting. Supports dataclasses, standard classes, function signatures, and more.
* [strongtyping](https://github.com/FelixTheC/strongtyping) ⭐ 121 | 🐛 6 | 🌐 Python | 📅 2026-08-08 - Decorator which checks whether the function is called with the correct type of parameters.
* [trycast](https://github.com/davidfstr/trycast) ⭐ 88 | 🐛 5 | 🌐 Python | 📅 2025-12-10 - Parse JSON-like values whose shape is defined by typed dictionaries (TypedDicts) and other standard Python type hints.
* [typedpy](https://github.com/loyada/typedpy) ⭐ 17 | 🐛 3 | 🌐 Python | 📅 2024-09-24 - Type-safe, strict Python. Works well with standard Python.

## Stub packages

* [boto3-stubs](https://vemel.github.io/boto3_stubs_docs/) - Stubs for [boto3](https://github.com/boto/boto3) ⭐ 9,893 | 🐛 192 | 🌐 Python | 📅 2026-09-02.
* [typeshed](https://github.com/python/typeshed) ⭐ 5,118 | 🐛 369 | 🌐 Python | 📅 2026-09-03 - Collection of library stubs, with static types.
* [django-stubs](https://github.com/typeddjango/django-stubs) ⭐ 1,972 | 🐛 175 | 🌐 Python | 📅 2026-09-03 - Stubs for [Django](https://github.com/django/django) ⭐ 89,931 | 🐛 484 | 🌐 Python | 📅 2026-09-03.
* [asgiref](https://github.com/django/asgiref) ⭐ 1,632 | 🐛 67 | 🌐 Python | 📅 2026-08-28 - ASGI specification, provides [asgiref.typing](https://github.com/django/asgiref/blob/main/asgiref/typing.py) ⭐ 1,632 | 🐛 67 | 🌐 Python | 📅 2026-08-28 module with type annotations for ASGI servers.
* [torchtyping](https://github.com/patrick-kidger/torchtyping) ⭐ 1,482 | 🐛 16 | 🌐 Python | 📅 2025-05-02 - Enhanced type annotations for [PyTorch](https://pytorch.org/).
* [types-aiobotocore](https://vemel.github.io/types_aiobotocore_docs/) - Stubs for [aiobotocore](https://github.com/aio-libs/aiobotocore) ⭐ 1,426 | 🐛 23 | 🌐 Python | 📅 2026-09-01.
* [sqlalchemy-stubs](https://github.com/dropbox/sqlalchemy-stubs) ⭐ 583 | 🐛 87 | 🌐 Python | 📅 2024-06-10 - Stubs for [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy) ⭐ 12,130 | 🐛 206 | 🌐 Python | 📅 2026-09-02.
* [djangorestframework-stubs](https://github.com/typeddjango/djangorestframework-stubs) ⭐ 540 | 🐛 63 | 🌐 Python | 📅 2026-09-01 - Stubs for [DRF](https://github.com/encode/django-rest-framework) ⭐ 30,156 | 🐛 57 | 🌐 Python | 📅 2026-09-03.
* [celery-types](https://github.com/sbdchd/celery-types) ⭐ 156 | 🐛 13 | 🌐 Python | 📅 2026-08-28 - Type stubs for [Celery](https://github.com/celery/celery) ⭐ 28,854 | 🐛 741 | 🌐 Python | 📅 2026-09-03 and its related packages [django-celery-results](https://github.com/celery/django-celery-results) ⭐ 785 | 🐛 63 | 🌐 Python | 📅 2026-08-31, [ampq](https://github.com/celery/py-amqp) ⭐ 316 | 🐛 45 | 🌐 Python | 📅 2026-07-04, [kombu](https://github.com/celery/kombu) ⭐ 3,138 | 🐛 215 | 🌐 Python | 📅 2026-09-03, [billiard](https://github.com/celery/billiard) ⭐ 435 | 🐛 88 | 🌐 Python | 📅 2026-08-17, [vine](https://github.com/celery/vine) ⭐ 128 | 🐛 14 | 🌐 Python | 📅 2026-09-01 and [ephem](https://github.com/brandon-rhodes/pyephem) ⭐ 893 | 🐛 4 | 🌐 C | 📅 2026-04-30.
* [scipy-stubs](https://github.com/jorenham/scipy-stubs) ⭐ 94 | 🐛 14 | 🌐 Python | 📅 2026-09-03 - Stubs for [SciPy](https://github.com/scipy/scipy) ⭐ 14,985 | 🐛 1,824 | 🌐 Python | 📅 2026-09-03.
* [botostubs](https://github.com/jeshan/botostubs) ⭐ 91 | 🐛 11 | 🌐 Python | 📅 2023-02-07 - Gives you code assistance for any boto3 API in any IDE.
* [PyQt5-stubs](https://github.com/stlehmann/PyQt5-stubs) ⭐ 71 | 🐛 13 | 🌐 Python | 📅 2023-07-23 - Stubs for [PyQt5](https://www.riverbankcomputing.com/software/pyqt/intro).
* [lxml-stubs](https://github.com/lxml/lxml-stubs) ⚠️ Archived - Stubs for [lxml](https://lxml.de).
* [grpc-stubs](https://github.com/shabbyrobe/grpc-stubs) ⚠️ Archived - Stubs for [grpc](https://github.com/grpc/grpc) ⭐ 45,290 | 🐛 1,349 | 🌐 C++ | 📅 2026-09-03.
* [pythonista-stubs](https://github.com/hbmartin/pythonista-stubs) ⭐ 23 | 🐛 6 | 🌐 Python | 📅 2025-08-13 - Stubs for [Pythonista](http://omz-software.com/pythonista/docs/ios/).
* [python-phonenumbers-stubs](https://github.com/AA-Turner/python-phonenumbers-stubs) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-09-01 - Stubs for [phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) ⭐ 3,768 | 🐛 12 | 🌐 Python | 📅 2026-08-28.
* [sqlalchemy2-stubs](https://docs.sqlalchemy.org/en/14/orm/extensions/mypy.html) - Official stubs and mypy plugin for [SQLAlchemy](https://www.sqlalchemy.org).

## Additional types

* [returns](https://github.com/dry-python/returns) ⭐ 4,357 | 🐛 81 | 🌐 Python | 📅 2026-09-01 - Make your functions return something meaningful, typed, and safe.
* [phantom-types](https://github.com/antonagestam/phantom-types) ⭐ 233 | 🐛 17 | 🌐 Python | 📅 2026-01-01 - Phantom types.
* [useful-types](https://github.com/hauntsaninja/useful_types) ⭐ 153 | 🐛 19 | 🌐 Python | 📅 2026-07-06 - Collection of useful protocols and type aliases.
* [option](https://github.com/MaT1g3R/option) ⭐ 103 | 🐛 8 | 🌐 Python | 📅 2024-01-01 - Rust like Option and Result types.
* [optype](https://github.com/jorenham/optype) ⭐ 94 | 🐛 26 | 🌐 Python | 📅 2026-09-03 - Opinionated `collections.abc` and `operators` alternative: Flexible single-method protocols and typed operators with predictable names.
* [meiga](https://github.com/alice-biometrics/meiga) ⭐ 82 | 🐛 1 | 🌐 Python | 📅 2024-10-22 - Simple, typed and monad-based Result type.
* [safetywrap](https://github.com/mplanchard/safetywrap) ⭐ 46 | 🐛 0 | 🌐 Python | 📅 2020-09-23 - Fully typesafe, Rust-like Result and Option types.
* [typet](https://github.com/contains-io/typet) ⚠️ Archived - Length-bounded types, dynamic object validation.

## Backports and improvements

* [typing-extensions](https://github.com/python/typing_extensions) ⭐ 583 | 🐛 18 | 🌐 Python | 📅 2026-08-31 - Backported and experimental type hints.
* [future-typing](https://github.com/PrettyWood/future-typing) ⭐ 20 | 🐛 5 | 🌐 Python | 📅 2021-05-14 - Backport for type hinting generics in standard collections and union types as `X | Y`.
* [typing-utils](https://github.com/bojiang/typing_utils) ⭐ 12 | 🐛 2 | 🌐 Python | 📅 2022-11-09 - Backport 3.8+ runtime typing utils(for eg: get\_origin) & add issubtype & more.

## Tools

### Linters

* [Ruff](https://github.com/astral-sh/ruff/) ⭐ 49,465 | 🐛 2,161 | 🌐 Rust | 📅 2026-09-03 - Extremely fast linter which supports lint rules from many other lint tools, such as flake8.
* [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) ⭐ 2,898 | 🐛 14 | 🌐 Python | 📅 2026-09-03 - The strictest and most opinionated Python linter ever.
* [flake8-annotations](https://github.com/sco1/flake8-annotations) ⭐ 165 | 🐛 0 | 🌐 Python | 📅 2026-07-10 - Plugin for flake8 to check for presence of type annotations in function definitions.
* [flake8-type-checking](https://github.com/snok/flake8-type-checking) ⭐ 128 | 🐛 4 | 🌐 Python | 📅 2026-02-18 - Plugin to help you guard any type-annotation-only import correctly.
* [flake8-typing-only-imports](https://github.com/sondrelg/flake8-typing-only-imports) ⭐ 128 | 🐛 4 | 🌐 Python | 📅 2026-02-18 - flake8 plugin that helps identify which imports to put into type-checking blocks, and how to adjust your type annotations once imports are moved.
* [flake8-pyi](https://github.com/ambv/flake8-pyi) ⭐ 83 | 🐛 23 | 🌐 Python | 📅 2026-07-24 - Plugin for Flake8 that provides specializations for type hinting stub files.
* [flake8-typing-imports](https://github.com/asottile/flake8-typing-imports) ⭐ 51 | 🐛 0 | 🌐 Python | 📅 2026-08-17 - Plugin which checks that typing imports are properly guarded.
* [flake8-annotations-complexity](https://github.com/best-doctor/flake8-annotations-complexity) ⭐ 50 | 🐛 3 | 🌐 Python | 📅 2026-08-14 - Plugin for flake8 to validate annotations complexity.
* [flake8-type-ignore](https://gitlab.com/jonafato/flake8-type-ignore/) - flake8 plugin to disallow type: ignore comments in your typed Python code.

### Testing

* [pytest-mypy](https://github.com/dbader/pytest-mypy) ⭐ 257 | 🐛 8 | 🌐 Python | 📅 2026-06-13 - Mypy static type checker plugin for Pytest.
* [pytest-mypy-plugins](https://github.com/typeddjango/pytest-mypy-plugins) ⭐ 126 | 🐛 24 | 🌐 Python | 📅 2026-08-19 - Pytest plugin for testing mypy types, stubs, and plugins.
* [pytest-mypy-testing](https://github.com/davidfritzsche/pytest-mypy-testing) ⭐ 34 | 🐛 10 | 🌐 Python | 📅 2026-01-26 - Pytest plugin to test mypy static type analysis.
* [mypy-test](https://github.com/orsinium-labs/mypy-test) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-10-24 - Test mypy plugins, stubs, custom types.

### Working with types

* [mypyc](https://github.com/python/mypy/tree/master/mypyc) ⭐ 20,627 | 🐛 3,226 | 🌐 Python | 📅 2026-09-03 - Compiles mypy-annotated, statically typed Python modules into CPython C extensions.
* [merge-pyi](https://github.com/google/pytype/tree/master/pytype/tools/merge_pyi) ⚠️ Archived - Part of pytype toolchain, applies stub files onto source code.
* [mypy-protobuf](https://github.com/dropbox/mypy-protobuf) ⭐ 708 | 🐛 32 | 🌐 Python | 📅 2026-04-28 - Tool to generate mypy stubs from protobufs.
* [typing-inspect](https://github.com/ilevkivskyi/typing_inspect) ⭐ 375 | 🐛 24 | 🌐 Python | 📅 2026-01-18 - The typing\_inspect module defines experimental API for runtime inspection of types defined in the `typing` module.
* [com2ann](https://github.com/ilevkivskyi/com2ann) ⭐ 158 | 🐛 10 | 🌐 Python | 📅 2025-06-02 - Tool for translation of type comments to type annotations.
* [retype](https://github.com/ambv/retype) ⭐ 145 | 🐛 1 | 🌐 Python | 📅 2022-08-14 - Another tool to apply stubs to code.
* [typesplainer](https://github.com/wasi-master/typesplainer) ⭐ 84 | 🐛 0 | 🌐 Python | 📅 2026-05-27 - A Python type explainer.
* [mypy-baseline](https://github.com/orsinium-labs/mypy-baseline) ⭐ 82 | 🐛 1 | 🌐 Python | 📅 2026-04-13 - Integrate mypy with existing codebase. A CLI tool that filters out existing type errors and reports only new ones.
* [typeforce](https://github.com/orsinium-labs/typeforce) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2022-09-30 - CLI tool that enriches your Python environment with type annotations, empowering mypy.
* [mypy-silent](https://github.com/whtsky/mypy-silent/) ⭐ 19 | 🐛 13 | 🌐 Python | 📅 2026-08-29 - Silence mypy by adding or removing code comments.
* [typing-json](https://pypi.org/project/typing-json/) - Lib for working with typed objects and JSON.

### Helper tools to add annotations to existing code

* [pytype annotate-ast](https://github.com/google/pytype/tree/master/pytype/tools/annotate_ast) ⚠️ Archived - A work-in-progress tool to annotate the nodes of an AST with their Python types.
* [monkeytype](https://github.com/instagram/MonkeyType) ⭐ 4,998 | 🐛 78 | 🌐 Python | 📅 2026-02-11 - Collects runtime types of function arguments and return values, and can automatically generate stub files or even add draft type annotations directly to your code based on the types collected at runtime.
* [pyannotate](https://github.com/dropbox/pyannotate) ⭐ 1,442 | 🐛 40 | 🌐 Python | 📅 2026-07-06 - Insert annotations into your source code based on call arguments and return types observed at runtime.
* [RightTyper](https://github.com/RightTyper/RightTyper) ⭐ 358 | 🐛 20 | 🌐 Python | 📅 2026-05-22 - A tool that generates types for your function arguments and return values. RightTyper lets your code run at nearly full speed with almost no memory overhead.
* [autotyping](https://github.com/JelleZijlstra/autotyping) ⭐ 288 | 🐛 8 | 🌐 Python | 📅 2025-09-19 - Automatically add simple return type annotations for functions (bool, None, Optional).
* [pytest-annotate](https://github.com/kensho-technologies/pytest-annotate) ⭐ 113 | 🐛 0 | 🌐 Python | 📅 2022-06-07 - Pyannotate plugin for pytest.
* [no\_implicit\_optional](https://github.com/hauntsaninja/no_implicit_optional) ⭐ 109 | 🐛 3 | 🌐 Python | 📅 2023-11-25 - A codemod to make your implicit optional type hints [PEP 484](https://peps.python.org/pep-0484/#union-types) compliant.
* [infer-types](https://github.com/orsinium-labs/infer-types) ⭐ 102 | 🐛 0 | 🌐 Python | 📅 2023-03-17 - CLI tool to automatically infer and add type annotations into Python code.
* [jsonschema-gentypes](https://github.com/camptocamp/jsonschema-gentypes) ⭐ 48 | 🐛 19 | 🌐 Python | 📅 2026-09-03 - Generate Python types based on TypedDict from a JSON Schema.
* [pytest-monkeytype](https://github.com/mariusvniekerk/pytest-monkeytype) ⭐ 46 | 🐛 2 | 🌐 Python | 📅 2020-07-29 - MonkeyType plugin for pytest.
* [auto-optional](https://github.com/Luttik/auto-optional) ⭐ 20 | 🐛 5 | 🌐 Python | 📅 2026-05-10 - Makes typed arguments Optional when the default argument is `None`.
* [PyTypes](https://github.com/pvs-hd-tea/PyTypes) ⭐ 12 | 🐛 9 | 🌐 Python | 📅 2022-08-29 - Infer Types by Python Tracing.

### Mypy plugins

* [mypy/plugins](https://github.com/python/mypy/tree/master/mypy/plugins) ⭐ 20,627 | 🐛 3,226 | 🌐 Python | 📅 2026-09-03 - Plugins already integrated into mypy.
* [mypy-zope](https://github.com/Shoobx/mypy-zope) ⭐ 40 | 🐛 19 | 🌐 Python | 📅 2026-07-15 - Plugin for [zope.interface](https://zopeinterface.readthedocs.io/en/latest/) support.
* [kubernetes-typed](https://github.com/gordonbondon/kubernetes-typed) ⭐ 26 | 🐛 3 | 🌐 Python | 📅 2024-09-08 - Plugin for Kubernetes [CRD](https://kubernetes.io/docs/tasks/extend-kubernetes/custom-resources/custom-resource-definitions/) type checking.
* [loguru-mypy](https://github.com/kornicameister/loguru-mypy) ⭐ 22 | 🐛 16 | 🌐 Python | 📅 2024-05-01 - Plugin for [loguru](https://github.com/Delgan/loguru) ⭐ 24,091 | 🐛 253 | 🌐 Python | 📅 2026-08-30 support.
* [pynamodb-mypy](https://github.com/pynamodb/pynamodb-mypy) ⭐ 5 | 🐛 2 | 🌐 Python | 📅 2022-10-21 - Plugin for [PynamoDB](https://github.com/pynamodb/PynamoDB) ⭐ 2,647 | 🐛 319 | 🌐 Python | 📅 2026-05-29 support.
* [NumPy](https://numpy.org/devdocs/reference/typing.html) - Plugin for [NumPy](https://numpy.org) support.
* [pydantic](https://docs.pydantic.dev/latest/integrations/mypy/) - Plugin for additional [Pydantic](https://docs.pydantic.dev/latest/) support.

## Integrations

* [pylance](https://github.com/microsoft/pylance-release) ⭐ 2,117 | 🐛 35 | 🌐 Python | 📅 2026-09-02 - PyRight integration for VSCode.
* [nbQA](https://github.com/nbQA-dev/nbQA) ⭐ 1,204 | 🐛 22 | 🌐 Python | 📅 2026-08-31 - Run type checkers (e.g. Mypy) on Jupyter Notebooks.
* [mypy-pycharm-plugin](https://github.com/dropbox/mypy-PyCharm-plugin) ⭐ 319 | 🐛 19 | 🌐 Java | 📅 2021-06-23 - Mypy integration for PyCharm.
* [vim-mypy](https://github.com/Integralist/vim-mypy) ⭐ 102 | 🐛 2 | 🌐 VimL | 📅 2019-10-08 - Mypy integration for Vim.
* [mypy-playground](https://github.com/ymyzk/mypy-playground) ⭐ 77 | 🐛 45 | 🌐 Python | 📅 2026-08-31 - Online playground for mypy.
* [emacs-flycheck-mypy](https://github.com/lbolla/emacs-flycheck-mypy) ⭐ 38 | 🐛 2 | 🌐 Emacs Lisp | 📅 2020-03-30 - Mypy integration for Emacs.

## Articles

### PEPs

* [PEP-3107](https://www.python.org/dev/peps/pep-3107) - Function Annotations.
* [PEP-482](https://www.python.org/dev/peps/pep-0482/) - Literature Overview for Type Hints.
* [PEP-483](https://www.python.org/dev/peps/pep-0483/) - The Theory of Type Hints.
* [PEP-484](https://www.python.org/dev/peps/pep-0484/) - Type Hints.
* [PEP-526](https://www.python.org/dev/peps/pep-0526/) - Syntax for Variable Annotations.
* [PEP-544](https://www.python.org/dev/peps/pep-0544/) - Protocols: Structural subtyping (static duck typing).
* [PEP-557](https://www.python.org/dev/peps/pep-0557/) - Data Classes.
* [PEP-560](https://www.python.org/dev/peps/pep-0560/) - Core support for typing module and generic types.
* [PEP-561](https://www.python.org/dev/peps/pep-0561/) - Distributing and Packaging Type Information.
* [PEP-563](https://www.python.org/dev/peps/pep-0563/) - Postponed Evaluation of Annotations.
* [PEP-585](https://www.python.org/dev/peps/pep-0585/) - Type Hinting Generics In Standard Collections.
* [PEP-586](https://www.python.org/dev/peps/pep-0586/) - Literal Types.
* [PEP-589](https://www.python.org/dev/peps/pep-0589/) - TypedDict: Type Hints for Dictionaries with a Fixed Set of Keys.
* [PEP-591](https://www.python.org/dev/peps/pep-0591/) - Adding a final qualifier to typing.
* [PEP-593](https://www.python.org/dev/peps/pep-0593/) - Flexible function and variable annotations.
* [PEP-604](https://www.python.org/dev/peps/pep-0604/) - Complementary syntax for Union\[].
* [PEP-612](https://www.python.org/dev/peps/pep-0612/) - Parameter Specification Variables.
* [PEP-613](https://www.python.org/dev/peps/pep-0613/) - Explicit Type Aliases.

### Third-party articles

* [1-minute guide to real constants in Python](https://sobolevn.me/2018/07/real-python-contants) - Full tutorial about `Final` constants and inheritance.
* [Simple dependent types in Python](https://sobolevn.me/2019/01/simple-dependent-types-in-python) - Full tutorial about `Literal` types.
* [Testing mypy stubs, plugins, and types](https://sobolevn.me/2019/08/testing-mypy-types) - Full tutorial about testing mypy types.
* [Our journey to type checking 4 million lines of Python](https://dropbox.tech/application/our-journey-to-type-checking-4-million-lines-of-python) - Dropbox has been one of the first companies to adopt Python static type checking at this scale.
* [PyTest MonkeyType Introduction](https://dev.to/ldrscke/type-annotate-an-existing-python-django-codebase-with-monkeytype-254i) - Type Annotate an existing Python Django Codebase with MonkeyType.
* [The state of type hints in Python](https://bernat.tech/posts/the-state-of-type-hints-in-python/) - As of May 2018.
* [Type hints cheat sheet](https://mypy.readthedocs.io/en/latest/cheat_sheet_py3.html) - Cheat sheet on writing type annotations by MyPy team.
* [Typechecking Django and DRF](https://sobolevn.me/2019/08/typechecking-django-and-drf) - Full tutorial about type-checking Django.
* [Type Check Your Django Application](https://kracekumar.com/post/type_check_your_django_app/) - An article based on two recent talks on adding type checks to Django.
* [typing](https://docs.python.org/3/library/typing.html) - Official Python documentation for `typing` module.
* [Python-typing-koans](https://github.com/kracekumar/python-typing-koans/) ⭐ 120 | 🐛 7 | 🌐 Python | 📅 2021-12-18 - A set of examples to learn optional static typing in Python.
* [Python Type Checking (Guide)](https://realpython.com/python-type-checking/) - In this guide, you will get a look into Python type checking.
* [Adding type hints to urllib3](https://sethmlarson.dev/blog/2021-10-18/tests-arent-enough-case-study-after-adding-types-to-urllib3) - Tests are not enough: Case study adding type hints to urllib3.
* [Adam Johnsons Blog](https://adamj.eu/tech/tag/mypy/) - Adam Johnson blogs about typing practices.
* [ParamSpec Guide](https://sobolevn.me/2021/12/paramspec-guide) - Newly released feature in `PEP612` allows you do a lot of advanced typing things with functions and their signatures.
* [Static Typing Python Decorators](https://rednafi.github.io/reflections/static-typing-python-decorators.html) - Accurately static typing decorators in Python is an icky business. The wrapper function obfuscates type information required to statically determine the types of the parameters and the return values of the wrapped function.
* [How do mypy, Pyright, and ty compare?](https://pydevtools.com/handbook/explanation/how-do-mypy-pyright-and-ty-compare/) - A detailed comparison of the three major Python static type checkers covering features, performance, and trade-offs.
* [ty: A Complete Guide](https://pydevtools.com/handbook/explanation/ty-complete-guide/) - Comprehensive guide to ty, the fast Python type checker from Astral.

## Related

* [awesome-python](https://github.com/vinta/awesome-python) ⭐ 317,989 | 🐛 18 | 🌐 Python | 📅 2026-09-01 - Curated list of awesome Python frameworks, libraries, software and resources.
* [python-typecheckers](https://github.com/ethanhs/python-typecheckers) ⭐ 75 | 🐛 1 | 📅 2026-03-19 - List of Python type checkers: static and runtime.
* [Python Developer Tooling Handbook](https://pydevtools.com/) - Comprehensive handbook covering Python type checkers, linters, and development tools with reference pages for [mypy](https://pydevtools.com/handbook/reference/mypy/), [Pyright](https://pydevtools.com/handbook/reference/pyright/), and [ty](https://pydevtools.com/handbook/reference/ty/).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-03._
