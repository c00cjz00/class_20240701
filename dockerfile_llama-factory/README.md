# DOCKER IMAGE BUILDING
```
# docker build -t c00cjz00/c00cjz00_pytorch:2.4.0-cuda11.8-cudnn9-devel .
# docker run -d --name llama-factory c00cjz00/c00cjz00_pytorch:2.4.0-cuda11.8-cudnn9-devel
# docker exec -it llama-factory bash
cd /workspace
git clone --depth 1 https://github.com/hiyouga/LLaMA-Factory.git
cd LLaMA-Factory/
pip install -r requirements.txt
pip install .[deepspeed,metrics,bitsandbytes]
#git clone https://github.com/ggerganov/llama.cpp.git
#pip install -r llama.cpp/requirements.txt


#echo "deb http://th.archive.ubuntu.com/ubuntu jammy main" >> /etc/apt/sources.list
#apt update
#apt install libc6
#strings /lib/x86_64-linux-gnu/libc.so.6 |grep GLIBC_
#add-apt-repository -y ppa:ubuntu-toolchain-r/test
#sudo apt install -y g++-11
#strings /usr/lib/x86_64-linux-gnu/libstdc++.so.6 | grep GLIBCXX



#docker login -u c00cjz00

#docker push c00cjz00/c00cjz00_pytorch:2.4.0-cuda11.8-cudnn9-devel


```
