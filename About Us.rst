About Us
========

Widget ini menampilkan informasi situs seperti deskripsi situs, alamat e-mail, nomor telepon dan alamat fisik.

Deskripsi Situs
---------------

#. Buka ``HTML Editor`` dengan cara klik menu **Tema > Edit HTML**.

   .. image:: _static/about/1.png

#. Klik sembarang di dalam kotak ``HTML Editor``

   .. image:: _static/about/2.png

#. Tekan ``Ctrl + F`` pada keyboard. Kemudian ketik **about us**, lalu tekan ``Enter``.

   .. image:: _static/about/3.png

#. Scroll ke bawah, maka Anda akan menemukan blok kode seperti berikut:

.. code-block:: html

    <h2 class='widget-title'>About Us</h2>
    <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus tincidunt magna eu purus porta tempor.
    </p>
    <dl class='addresses-info'>
        <div class='inf-item'>
            <dt class='l-ico'>
                <i aria-hidden='true' class='fa fa-envelope'/>
                <span class='sr'>e-mail address</span>
            </dt>
            <dd class='r-inf'>
                admin@example.com
            </dd>
        </div>
        <div class='inf-item'>
            <dt class='l-ico'>
                <i aria-hidden='true' class='fa fa-phone'/>
                <span class='sr'>phone number</span>
            </dt>
            <dd class='r-inf'>
                62-8XXXXXXXXXX<br/>62-8XXXXXXXXXX
            </dd>
        </div>
        <div class='inf-item'>
            <dt class='l-ico'>
                <i aria-hidden='true' class='fa fa-home'/>
                <span class='sr'>address</span>
            </dt>
            <dd class='r-inf'>
                4986 Woodside Circle<br/>Fort Walton Beach, FL 32547<br/>United States
            </dd>
        </div>
    </dl>

#. Ubah ``Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus tincidunt magna eu purus porta tempor.`` menjadi deskripsi singkat blog Anda.

Alamat E-mail
-------------

#. Lakukan langkah 1-4 seperti pada langkah-langkah di :ref:`Deskripsi Situs`.

#. Ubah ``admin@example.com`` dengan **Alamat E-Mail** yang anda inginkan (jika lebih dari 1, pisahkan dengan ``<br/>``). Contoh:

.. code-block:: html

    support@example.com<br/>cs@example.com

Nomor Telepon
-------------

#. Lakukan langkah 1-4 seperti pada langkah-langkah di :ref:`Deskripsi Situs`.

#. Ubah ``62-8XXXXXXXXXX<br/>62-8XXXXXXXXXX`` dengan **Nomor Telepon** yang anda inginkan. Jika lebih dari 1, pisahkan dengan ``<br/>``. Contoh:

.. code-block:: html

    62-838-2839-2918<br/>62-838-6281-7712

Alamat Fisik
------------

#. Lakukan langkah 1-4 seperti pada langkah-langkah di :ref:`Deskripsi Situs`.

#. Ubah ``4986 Woodside Circle<br/>Fort Walton Beach, FL 32547<br/>United States`` dengan **Alamat Fisik** yang anda inginkan (Gunakan ``<br/>`` untuk memberikan efek garis baru). Contoh::
4986 Woodside Circle<br/>Fort Walton Beach, FL 32547<br/>United States

.. tip:: Jika anda ingin menghapus salah satu detail di widget **About Us** silakan hapus dari ``<div class='inf-item'>`` sampai ``</div>`` terdekat. 

Contoh:
~~~~~~~

Hapus kode berikut ini:

.. code-block:: html

    <div class='inf-item'>
        <dt class='l-ico'>
        <i aria-hidden='true' class='fa fa-home'/>
        <span class='sr'>address</span>
        </dt>
        <dd class='r-inf'>
        4986 Woodside Circle<br/>Fort Walton Beach, FL 32547<br/>United States
        </dd>
    </div>
