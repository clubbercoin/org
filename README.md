Project: Clubbercoin
Project web page: http://clubbercoin.org
github: https://github.com/mediaemperor
freecode: http://freecode.com/projects/mediaemperor
Author: Hakan Nurhak
Copyright (c) 2017 Hakan Nurhak
This software is subject to the conditions detailed in the
LICENSE file provided within this distribution.
— in file src/CryptoNoteConfig.h — CLUBBERCOIN_NAME constant
const char CRYPTONOTE_NAME[clubbercoin] = "clubbercoin";
— in src/CMakeList.txt file — set_property(TARGET daemon PROPERTY OUTPUT_NAME "CLUBBERCOIN")
set_property(TARGET daemon PROPERTY OUTPUT_NAME "clubbercoin")
