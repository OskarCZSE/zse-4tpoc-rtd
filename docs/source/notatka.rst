========================
Składnia w reStructuredText
========================

Nagłówki tekstowe
=================

Nagłówek Poziom 1
==================

Nagłówek Poziom 2
------------------

Nagłówek Poziom 3
~~~~~~~~~~~~~~~~~~

Nagłówek Poziom 4
^^^^^^^^^^^^^^^^^^


Akapit tekstowy (treść)
========================

To jest akapit tekstowy. Składa się z kilku zdań, które są ze sobą powiązane i tworzą spójną całość.


Akapit informacyjny
====================

.. note::
   To jest informacja w formie notatki. Przykład ważnej informacji.

.. tip::
   To jest wskazówka, która może pomóc użytkownikowi w realizacji zadania.


Fragment kodu
==============

Liniowy kod:
``fragment kodu``

Blokowy kod:
.. code-block:: python3
   def example_function():
       print("To jest przykład funkcji.")

Odnośnik
========

Lokalny (Read the Docs):
`Link do sekcji <#nagłówek-poziom-1>`_

Zewnętrzny:
`Przykład zewnętrznego odnośnika <https://edu.gplweb.pl/?svc=Lesson_Asset&id=tida&lesson=27&class=4tp&load=85>`_


Listy
=====

Numerowana:
| 1. Pierwszy element
| 2. Drugi element
| 3. Trzeci element

Wypunktowana:
| * Pierwszy element
| * Drugi element
| * Trzeci element

Lista definicji:
Nazwa definicji
   Krótki opis lub definicja.


Obraz
=====

.. image:: https://docs.readthedocs.com/platform/stable/_static/logo.svg
   :alt: Alternatywny tekst dla obrazu
   :caption: Podpis pod obrazem


Tabela
======

+------------+-----------+
| Nagłówek 1 | Nagłówek 2|
+------------+-----------+
| Komórka 1  | Komórka 2 |
| Komórka 3  | Komórka 4 |
+------------+-----------+

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   usage
   kontakt
