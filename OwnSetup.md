git clone to the folder : /mnt/mnemo5/tao/d2l-en

the git repository dont contain code, download code : 
download direactly from course website (https://d2l.ai/chapter_preface/index.html, "Notebooks" on the bottom)
and upload/rename to the folder "/mnt/mnemo5/tao/d2l-en"
after unzip, got 4 subfolder :
jax, 
tensorflow
mxnet
pytorch



enviroment: 
conda create --name d2l python=3.9 -y

optinal: 
add kernel 
conda activate d2l
(d2l) tao@deimos:~/d2l-en$ conda install ipykernel
(d2l) tao@deimos:~/d2l-en$ python -m ipykernel install --user --name d2l --display-name "d2l"


then install pytorch: 
pip install torch==1.12.0 torchvision==0.13.0

then install some d2l package
pip install d2l==1.0.0b0: failed, 
tried https://github.com/openai/gym/issues/3176,  "pip install setuptools==65.5.0 pip==21"
succeed, but it downgrade pip , maybe not the best option, check
https://discuss.d2l.ai/t/installation/24/41 in future for more options 

å