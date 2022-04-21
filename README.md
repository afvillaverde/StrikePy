# About StrikePy

StrikePy is a Python toolbox that analyses nonlinear models of ordinary differential equations. It performs a simultaneous assessment of:
- state **observability**,
- parameter structural **identifiability**,  
- unknown **input observability**

The analysis is performed symbolically, and yields results that are valid **locally** for all values of the variables, except for a set of measure zero. 

StrikePy implements the FISPO algorithm from the MATLAB toolbox [STRIKE-GOLDD](https://github.com/afvillaverde/strike-goldd).
The motivation behind StrikePy is to provide a Python alternative to MATLAB. 
That said, it should be noted that STRIKE-GOLDD is computationally more efficient and includes more features than StrikePy.

StrikePy was created by **David Rey Rostro**, <davidreyrostro@gmail.com>, under the supervision of [Alejandro F. Villaverde](http://afvillaverde.webs.uvigo.gal/), <afvillaverde@uvigo.gal>. 

## Installation and requirements
StrikePy requires Python 3.9.

The required packages can be installed using pip: `pip install numpy sympy symbtools`

## Getting started
To use StrikePy you just need to follow these 3 steps: 
1. download the toolbox and install the required packages (see above), 
2. define the problem by editing 'options.py', or by creating a custom options file inside the 'custom_options' folder,
3. run the file 'RunModels.py' for a test, or follow the instructions in the file to analyse other models.
	
A number of examples are provided in the models folder.
 
## Results
The results of the analysed models as well as the observability/identifiability matrix will be saved in a .txt file in the results folder. 

More information about StrikePy can be found in the [StrikePy manual](StrikePy/doc/StrikePy_manual.pdf)

## Disclaimer

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, version 3 of the License.
    
This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  
See the GNU General Public License for more details.
 
You should have received a copy of the GNU General Public License along with this program. If not, see <http://www.gnu.org/licenses/>.
