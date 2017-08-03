Sosial Media
============

#. Buka ``HTML Editor`` dengan cara klik menu **Tema > Edit HTML**.

   .. image:: _static/about/1.png

#. Klik sembarang pada kotak ``HTML Editor``

   .. image:: _static/about/2.png

#. Tekan ``Ctrl+F`` pada keyboard. Kemudian ketik **connect</h2>**, lalu tekan ``Enter``.

#. Scroll ke bawah, maka Anda akan menemukan blok kode seperti berikut:

   .. image:: _static/sosial/1.png

#. #. Ganti ``#`` menjadi url Facebook Anda.

   #. Ganti ``#`` menjadi url Twitter Anda.

   #. Ganti ``#`` menjadi url Google+ Anda.

   #. Ganti ``#`` menjadi url Pinterest Anda.

   #. Ganti ``#`` menjadi url Instagram Anda.

#. Jika ingin menghapus salah satu ikon sosial media, maka hapus dari ``<a`` sampai ``</a>`` terdekat.

   **Contoh:** Jika saya ingin menghapus ikon instagram maka yang saya hapus adalah:

   .. code-block:: html

        <a href='#' title='a'>
            <i class='fa fa-instagram'/>
        </a>