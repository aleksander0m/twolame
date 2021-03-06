TwoLAME
=======

[![Travis Build Status](https://travis-ci.org/njh/twolame.svg?branch=master)](https://travis-ci.org/njh/twolame)

Based on tooLAME by Michael Cheng

All changes to the ISO source are licensed under the LGPL
(see COPYING for details)

    TwoLAME is free software; you can redistribute it and/or
    modify it under the terms of the GNU Lesser General Public
    License as published by the Free Software Foundation; either
    version 2.1 of the License, or (at your option) any later version.

    TwoLAME is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
    Lesser General Public License for more details.

    You should have received a copy of the GNU Lesser General Public
    License along with TwoLAME; if not, write to the Free Software
    Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA


INTRODUCTION
------------

TwoLAME is an optimized MPEG Audio Layer 2 (MP2) encoder.
It is based heavily on:

* tooLAME by Michael Cheng
* the ISO dist10 code
* improvement to algorithms as part of the LAME project (lame.sf.net)
* other contributors (see AUTHORS)

TwoLAME should be able to be used as a drop-in replacement for
LAME (a MPEG Layer 3 encoder). The frontend takes very similar
command line options to LAME, and the backend library has a very
similar API to LAME.

For the latest version of TwoLAME, visit the project homepage:
http://www.twolame.org/


MPEG Audio Layer 2 (MP2)
------------------------
(taken from Wikipedia article on MP2)

MP2 (sometimes incorrectly named Musicam) is a short form of MPEG Audio Layer II,
and it is also used as a file extension for files containing audio data of this
type. While it has largely been superseded by MP3 for PC and Internet applications,
it remains a dominant standard for audio broadcasting as part of the DAB digital
radio and DVB digital television standards. It is also used internally within the
radio industry, for example in NPR's PRSS Content Depot programming distribution
system.


INSTALLATION
------------

Standard automake process:

    ./configure
    make
    make install



REFERENCE PAPERS
----------------

(Specifically Layer II Papers)

Kumar, M & Zubair, M., A high performance software implementation of mpeg audio
encoder, 1996, ICASSP Conf Proceedings (I think)

Fischer, K.A., Calculation of the psychoacoustic simultaneous masked threshold
based on MPEG/Audio Encoder Model One, ICSI Technical Report, 1997
ftp://ftp.icsi.berkeley.edu/pub/real/kyrill/PsychoMpegOne.tar.Z

Hyen-O et al, New Implementation techniques of a real-time mpeg-2 audio encoding
system. p2287, ICASSP 99.

Imai, T., et al, MPEG-1 Audio real-time encoding system, IEEE Trans on Consumer
Electronics, v44, n3 1998. p888

Teh, D., et al, Efficient bit allocation algorithm for ISO/MPEG audio encoder,
Electronics Letters, v34, n8, p721

Murphy, C & Anandakumar, K, Real-time MPEG-1 audio coding and decoding on a DSP
Chip, IEEE Trans on Consumer Electronics, v43, n1, 1997 p40

Hans, M & Bhaskaran, V., A compliant MPEG-1 layer II audio decoder with 16-B
arithmetic operations, IEEE Signal Proc Letters v4 n5 1997 p121

