	/*
	Author: code34 nicolas_boiteux@yahoo.fr
	Copyright (C) 2017-2018 Nicolas BOITEUX

	CLASS OO_CIPHER OBJECT

	RC4 reference:
	https://fr.wikipedia.org/wiki/RC4
		
	This program is free software: you can redistribute it and/or modify
	it under the terms of the GNU General Public License as published by
	the Free Software Foundation, either version 3 of the License, or
	(at your option) any later version.
	
	This program is distributed in the hope that it will be useful,
	but WITHOUT ANY WARRANTY; without even the implied warranty of
	MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
	GNU General Public License for more details.
	
	You should have received a copy of the GNU General Public License
	along with this program.  If not, see <http://www.gnu.org/licenses/>. 
	*/

	Create a cipher object
	
	Usage:
		put the "oo_cipher.sqf" and the "oop.h" files in your mission directory
		put this code into your mission init.sqf
		call compilefinal preprocessFileLineNumbers "oo_cipher.sqf";

	See example mission in directory: init.sqf
	
	Licence: 
	You can share, modify, distribute this script but don't remove the licence and the name of the original author

	logs:
		0.5 - fix stream generation issue, mod, tune hexa to command line tools
		0.4 - re factory, add uncipher method
		0.3 - add 2048bits key - fix typo
		0.2 - add hexa convertion functions
		0.1 - OO CIPHER - first release with Rivest Cipher 4


