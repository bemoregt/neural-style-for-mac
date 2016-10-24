# neural-style-for-mac

neural-style running for Mac OS X, El Capitan/Sierra

How to install

# Install Torch for Mac OS X
git clone https://github.com/torch/ezinstall  

$ clean.sh
$ install-deps
$ install-torch+luajit

# Install loadcaffe 

$ luarocks install loadcaffe 

# Install protobuf

$ brew insrall protobuf

# Install etc.

$ luarocks install optim
$ luarocks install image
$ luarocks install nn
$ luarocks install nngraph

# Install neural style for mac

$ git clone https://github.com/jcjohnson/neural-style
$ sh model/download_model.sh

# Test now for cpu mode.

$ th neural_style.lua -gpu -1 ...

 You can also use the CUDA (eGPU or Nvidia Mac)

$ th neural_style.lua -gpu 0 ...


# My Youtube demo is here
https://www.youtube.com/watch?v=FJEtcLNaqCc


Enjoy the deep art ~
