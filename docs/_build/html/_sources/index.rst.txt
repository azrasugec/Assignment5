.. documentation-azrasugec documentation master file, created by
   sphinx-quickstart on Tue May 13 21:57:45 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

documentation-azrasugec documentation
=====================================

Add your content using ``reStructuredText`` syntax. See the
`reStructuredText <https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html>`_
documentation for details.

Merhaba!
========

Bu Assignment 5 için örnek bir yazıdır.

Örnek Kod
---------

Bubble Sort Example
===================

Below is a simple implementation of the **Bubble Sort** algorithm in Python:

.. code-block:: python

    def bubble_sort(arr):
        n = len(arr)
        for i in range(n):
            for j in range(0, n - i - 1):
                if arr[j] > arr[j + 1]:
                    # Swap the elements
                    arr[j], arr[j + 1] = arr[j + 1], arr[j]
        return arr

    # Example usage
    my_list = [64, 34, 25, 12, 22, 11, 90]
    sorted_list = bubble_sort(my_list)
    print("Sorted list:", sorted_list)

.. toctree::
   :maxdepth: 2
   :caption: Contents:

