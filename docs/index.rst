Colander
========

.. Colander is useful as a system for validating and deserializing data obtained
.. via XML, JSON, an HTML form post or any other equally simple data
.. serialization.  It runs on Python 2.6, 2.7 and 3.2.  Colander can be used to:

Colander は、 XML, JSON, HTML フォーム post 、あるいは他の同じくらい単純な
データシリアライズによって得られたデータをバリデーションして、
逆シリアライズするためのシステムとして有用です。 Python 2.6, 2.7, 3.2 上で
走ります。 Colander は次のことに使用できます:


.. - Define a data schema.

- データスキーマを定義する


.. - Deserialize a data structure composed of strings, mappings, and
..   lists into an arbitrary Python structure after validating the data
..   structure against a data schema.

- 文字列、マッピング、リストから構成されるデータ構造を、データスキーマに
  対してバリデーションした後で、任意の Python 構造に逆シリアライズする


.. - Serialize an arbitrary Python structure to a data structure composed
..   of strings, mappings, and lists.

- 任意の Python 構造を、文字列、マッピング、リストから構成されるデータ
  構造にシリアライズする


.. Colander is a good basis for form generation systems, data
.. description systems, and configuration systems.

Colander は、フォーム生成システム、データ記述システム、設定システムの
良い基盤です。


.. Out of the box, Colander can serialize and deserialize various types
.. of objects, including:

初期状態では、 Colander は、次のものを含む様々な型のオブジェクトを
シリアライズ/逆シリアライズすることができます:


.. - A mapping object (e.g. dictionary).

.. - A variable-length sequence of objects (each object is of the same
..   type).

.. - A fixed-length tuple of objects (each object is of a different
..   type).

.. - A string or Unicode object.

.. - An integer.

.. - A float.

.. - A decimal float.

.. - A boolean.

.. - An importable Python object (to a dotted Python object path).

.. - A Python ``datetime.datetime`` object.

.. - A Python ``datetime.date`` object.

- マッピングオブジェクト (例: 辞書)

- オブジェクトの可変長のシーケンス (各オブジェクトは同じ型)

- オブジェクトの固定長のタプル (各オブジェクトは異なる型)

- 文字列または Unicode オブジェクト

- 整数

- 浮動小数点数

- 10進浮動小数点数

- 真偽値

- インポート可能な Python オブジェクト (dotted Python オブジェクトパスに
  シリアライズされる)

- Python の ``datetime.datetime`` オブジェクト

- Python の ``datetime.date`` オブジェクト


.. Colander allows additional data structures to be serialized and
.. deserialized by allowing a developer to define new "types".

開発者が新しい「型」を定義することで Colander は追加のデータ構造を
シリアライズ/逆シリアライズすることができます。


.. The error messages used by Colander's default types are
.. internationalizable.

Colander のデフォルト型で使用されるエラーメッセージは国際化可能です。


.. toctree::
   :maxdepth: 2

   basics.rst
   null.rst
   extending.rst
   binding.rst
   manipulation.rst
   interfaces.rst
   api.rst
   glossary.rst
   changes.rst


Indices and tables
------------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

