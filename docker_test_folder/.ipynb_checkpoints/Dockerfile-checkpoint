#FROM 63104351884.dkr.ecr.us-east-1.amazonaws.com/pytorch-training:1.7.1-gpu-py36-cu110-ubuntu18.04
#FROM 683313688378.dkr.ecr.us-east-1.amazonaws.com/pytorch-training:1.7.1-gpu-py36-cu110-ubuntu18.04
#FROM 763104351884.dkr.ecr.us-east-1.amazonaws.com/pytorch-training:1.5.1-cpu-py36-ubuntu16.04
FROM 763104351884.dkr.ecr.us-east-1.amazonaws.com/pytorch-training:1.7.1-gpu-py36-cu110-ubuntu18.04

RUN pip install soundfile

#ENTRYPOINT bash

#RUN conda install -y -c conda-forge librosa

RUN pip install torchaudio

RUN conda install -y -c conda-forge librosa

RUN pip install tensorflow
RUN pip install tensorflow-addons
RUN pip install tqdm
RUN pip install pysoundfile
RUN pip install scipy

RUN pip install flask