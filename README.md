# tekniskmuseum2023
Eksempelkode fra FFI/ITS maskinlæringsdemo

Mitt forslag til "setup" for maskinlæringsmiljø:
Installer Miniconda fra https://docs.conda.io/en/latest/miniconda.html
Kan etterpå startes via startmenyen: <start> Anaconda Powershell prompt
Lag et nytt "env" og installer pytorch, matplotlib og jupyter:

#conda create -n MITT_NAVN python=3.9
#conda activate MITT_NAVN
#conda install pytorch torchvision cpuonly -c pytorch
#conda install matplotlib
#conda install jupyter

I samme miljø (dvs gjennom Anaconda prompt og etter conda activate <navn> kan du nå starte programmeringsmiljøet:
#jupyter notebook
Vanligvis vil du da automatisk få opp Jupyter i en nettleser
