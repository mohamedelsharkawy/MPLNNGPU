# The MPL NN on GPU #

## Introduce ##

This project is based on the project here http://www.mathworks.com/matlabcentral/fileexchange/54076-mlp-neural-network-with-backpropagation .
I just trans it into GPU version.

![preview](/Final Result for 2 Spirals.png)

## Requirement ##

* Matlab
* Nvidia Cuda Accelerate card


## Licence ##

_Copyright © `2016`, `manageryzy@gmail.com`_
_All rights reserved._

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright
   notice, this list of conditions and the following disclaimer.
2. Redistributions in binary form must reproduce the above copyright
   notice, this list of conditions and the following disclaimer in the
   documentation and/or other materials provided with the distribution.
3. Neither the name of the `manageryzy@gmail.com` nor the
   names of its contributors may be used to endorse or promote products
   derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS “AS IS” AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL `manageryzy@gmail.com` BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

## Original Readme ##

    %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
    % Multilayer Perceptron (MLP) Neural Network Function using MATLAB:       %
    %  An implementation for Multilayer Perceptron Feed Forward Fully         %
    %  Connected Neural Network with a sigmoid activation function. The       %
    %  training is done using the Backpropagation algorithm with options for  %
    %  Resilient Gradient Descent, Momentum Backpropagation, and Learning     %
    %  Rate Decrease. The training stops when the Mean Square Error (MSE)     %
    %  reaches zero or a predefined maximum number of epochs is reached.      %
    %                                                                         %
    %  Four example data for training and testing are included with the       %
    %  project. They are generated by SharkTime Sharky Neural Network         %
    %   (http://sharktime.com/us_SharkyNeuralNetwork.html)                    %
    %                                                                         %
    % Copyright (C) 9-2015 Hesham M. Eraqi. All rights reserved.              %
    %                    hesham.eraqi@gmail.com                               %
    %                                                                         %
    %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

## FAQ ##

* I can't run it.
* Please use the latest matlab and check you graphics card support CUDA


* Do it support octave?
* I'm afraid not.