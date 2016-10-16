# neural-style-for-mac
neural-style running for Mac OS X, El Capitan/Sierra

How to install

1. Install Torch for Mac OS X
git clone https://github.com/torch/ezinstall  

$ clean.sh
$ install-deps
$ install-torch+luajit

2. Install loadcaffe 

$ luarocks install loadcaffe 

3. Install protobuf

$ brew insrall protobuf

4. Install etc.

$ luarocks install optim
$ luarocks install image
$ luarocks install nn
$ luarocks install nngraph

5. Install neural style for mac

$ git clone https://github.com/jcjohnson/neural-style
$ sh model/download_model.sh

6. Test now for cpu mode.

$ th neural_style.lua -gpu -1 ...

You can also use the CUDA (eGPU or Nvidia Mac)

$ th neural_style.lua -gpu 0 ...

Enjoy the deep art ~
