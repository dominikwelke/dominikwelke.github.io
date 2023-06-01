.. title: New contribution: Eye Tracking support for MNE Python 
.. slug: 2023-03-mne-eyetracking
.. date: 2023-03-28 09:12:26 UTC+02:00
.. tags: coding, open-science
.. category: 
.. link: 
.. description: 
.. type: text

Last year I won a scholarship to participate in MNE-Python 2022 Code Sprint.
Besides some fixes and work in the documentation my main goal was to enable MNE to read and support Eye Tracking data.

We now merged a first big PR (thanks to `Scott Huberty <https://github.com/scott-huberty>`_ for joining me in the effort and pushing us forward!):

MNE now has a dedicated class for eye tracking data and can import SR Research's proprietary ASCII files (or work with data in numpy arrays).
Check out the first tutorials `here <https://mne.tools/stable/auto_tutorials/io/70_reading_eyetracking_data.html>`__  and `here <https://mne.tools/stable/auto_tutorials/preprocessing/90_eyetracking_data.html>`__ ;)
