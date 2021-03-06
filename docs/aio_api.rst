.. currentmodule:: compuglobal.aio

Async API Reference
===================

CompuGlobal allows for both random and searchable screencaps, images and gifs
embedded with default or custom captions for the following shows:

*The Simpsons, Futurama, Rick and Morty, West Wing and 30 Rock.*

.. note::

    This library relies upon undocumented external APIs.

Contents
--------
.. toctree::
    aio_full
    aio_screencap
    frame

API Endpoints
-------------

.. autoclass:: CompuGlobalAPI
    :noindex:

    .. autocomethod:: compuglobal.aio.CompuGlobalAPI.get_screencap
        :noindex:
    .. autocomethod:: compuglobal.aio.CompuGlobalAPI.get_random_screencap
        :noindex:
    .. autocomethod:: compuglobal.aio.CompuGlobalAPI.search
        :noindex:
    .. autocomethod:: compuglobal.aio.CompuGlobalAPI.search_for_screencap
        :noindex:
    .. autocomethod:: compuglobal.aio.CompuGlobalAPI.get_frames
        :noindex:
    .. autocomethod:: compuglobal.aio.CompuGlobalAPI.generate_gif
        :noindex:

Errors
------
.. autoclass:: APIPageStatusError
    :members:

.. autoclass:: NoSearchResultsFound
    :members:

Supported APIs
--------------

Frinkiac
~~~~~~~~
.. autoclass:: Frinkiac
    :members:
    :noindex:

Morbotron
~~~~~~~~~
.. autoclass:: Morbotron
    :members:
    :noindex:

Master Of All Science
~~~~~~~~~~~~~~~~~~~~~
.. autoclass:: MasterOfAllScience
    :members:
    :noindex:

Good God Lemon
~~~~~~~~~~~~~~
.. autoclass:: GoodGodLemon
    :members:
    :noindex:

Capital Beat Us
~~~~~~~~~~~~~~~
.. autoclass:: CapitalBeatUs
    :members:
    :noindex:

FrinkiHams
~~~~~~~~~~
.. autoclass:: FrinkiHams
    :members:
    :noindex:
