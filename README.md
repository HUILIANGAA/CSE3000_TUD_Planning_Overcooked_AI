# CSE3500_TUD_Planning_Overcooked_AI
Code used to run experiments for planning experiments in Overcooked AI, CSE3500 at the TU Delft.

To run the code (you should be able to inspect the results in the jupyter notebooks without setting up), follow these steps:
1. Follow the guide from https://github.com/HumanCompatibleAI/human_aware_rl/tree/neurips2019
2. Setup all the related libraries (list of versions to install directly below) suitable for the neurips branch.
3. Put all the files except agent.py in the human_aware_rl/human_aware_rl folder.
4. Replace agent.py in human_aware_rl/overcooked_ai/overcooked_ai_py/agents with the one provided in this repo. (note that I added code to the existing code from the neurips branch).
5. Open the .ipynb files using model_conversion in conda as used in step 1.

Relevant notebooks are:
- CP_HProxy_Experimental_changes
- CP+CP
- CP+HProxy_CORRECT
- CP+HProxy_Experimental_opposite_direction
- Nils_Graphs
- Planning_Summarized_Nils
- NeurIPS Experiments and Visualizations -> not created by me, only run by me.
- P_BC_neurips

The following library versions worked for me (in model_conversion conda):
- Note: there are certainly unused libraries included.
- 
1.Package                       2.Version             (3.Editable project location)
----------------------------- ------------------- ------------------------------------------
absl-py                       1.0.0
alabaster                     0.7.12
ale-py                        0.7.5
argon2-cffi                   21.3.0
argon2-cffi-bindings          21.2.0
astor                         0.8.1
asttokens                     2.0.5
astunparse                    1.6.3
atari-py                      0.2.6
attrs                         21.4.0
Babel                         2.10.1
backcall                      0.2.0
baselines                     0.1.5               /home/nils/human_aware_rl/baselines
beautifulsoup4                4.11.1
bleach                        5.0.0
cached-property               1.5.2
cachetools                    5.0.0
certifi                       2021.10.8
cffi                          1.15.0
charset-normalizer            2.0.12
click                         8.1.2
cloudpickle                   1.6.0
colorama                      0.4.4
coverage                      6.3.2
cycler                        0.11.0
Cython                        0.29.28
debugpy                       1.6.0
decorator                     5.1.1
defusedxml                    0.7.1
dill                          0.3.4
docopt                        0.6.2
docutils                      0.17.1
entrypoints                   0.4
executing                     0.8.3
fastjsonschema                2.15.3
flatbuffers                   2.0
gast                          0.5.3
gitdb                         4.0.9
GitPython                     3.1.27
glob2                         0.7
google-auth                   2.6.6
google-auth-oauthlib          0.4.6
google-pasta                  0.2.0
grpcio                        1.44.0
gym                           0.21.0
gym-notices                   0.0.6
h5py                          2.8.0
human-aware-rl                0.0.1               /home/nils/human_aware_rl
idna                          3.3
imagesize                     1.3.0
importlib-metadata            4.11.3
importlib-resources           5.7.1
iniconfig                     1.1.1
ipykernel                     6.13.0
ipython                       7.33.0
ipython-genutils              0.2.0
ipywidgets                    8.0.0rc0
jedi                          0.18.1
Jinja2                        3.1.1
joblib                        1.1.0
jsonpickle                    0.7.2
jsonschema                    4.4.0
jupyter                       1.0.0
jupyter-client                7.2.2
jupyter-console               6.4.3
jupyter-core                  4.10.0
jupyterlab-pygments           0.2.2
jupyterlab-widgets            3.0.0rc0
Keras                         2.2.2
Keras-Applications            1.0.4
Keras-Preprocessing           1.0.2
kiwisolver                    1.4.2
libclang                      14.0.1
livereload                    2.6.3
Markdown                      3.3.6
MarkupSafe                    2.1.1
matplotlib                    3.0.3
matplotlib-inline             0.1.3
memory-profiler               0.60.0
mistune                       0.8.4
mock                          4.0.3
more-itertools                8.12.0
mpi4py                        3.1.3
munch                         2.5.0
nbclient                      0.6.2
nbconvert                     6.5.0
nbformat                      5.3.0
nest-asyncio                  1.5.5
notebook                      6.4.11
numpy                         1.21.6
oauthlib                      3.2.0
opencv-python                 4.5.5.64
opt-einsum                    3.3.0
overcooked-ai                 0.0.1               /home/nils/human_aware_rl/overcooked_ai
packaging                     21.3
pandas                        1.3.5
pandocfilters                 1.5.0
parso                         0.8.3
pexpect                       4.8.0
pickleshare                   0.7.5
pip                           22.0.4
pluggy                        0.6.0
progressbar2                  4.0.0
prometheus-client             0.14.1
prompt-toolkit                3.0.29
protobuf                      3.20.1
psutil                        5.9.0
ptyprocess                    0.7.0
pure-eval                     0.2.2
py                            1.11.0
py-cpuinfo                    8.0.0
pyasn1                        0.4.8
pyasn1-modules                0.2.8
pycparser                     2.21
pygame                        1.9.5
pyglet                        2.0a4
Pygments                      2.12.0
pymongo                       4.1.1
pyparsing                     3.0.8
pyrsistent                    0.18.1
pytest                        3.5.1
pytest-cov                    2.6.0
python-dateutil               2.8.2
python-utils                  3.1.0
pytz                          2022.1
PyYAML                        6.0
pyzmq                         23.0.0b1
qtconsole                     5.3.0
QtPy                          2.1.0
requests                      2.27.1
requests-oauthlib             1.3.1
rsa                           4.8
sacred                        0.7.4
scipy                         1.7.3
seaborn                       0.9.0
Send2Trash                    1.8.0
setuptools                    61.2.0
six                           1.11.0
smmap                         5.0.0
snowballstemmer               2.2.0
soupsieve                     2.3.2.post1
Sphinx                        4.5.0
sphinx-autobuild              2021.3.14
sphinx-rtd-theme              1.0.0
sphinxcontrib-applehelp       1.0.2
sphinxcontrib-devhelp         1.0.2
sphinxcontrib-htmlhelp        2.0.0
sphinxcontrib-jsmath          1.0.1
sphinxcontrib-qthelp          1.0.3
sphinxcontrib-serializinghtml 1.1.5
stable-baselines              2.5.1a0             /home/nils/human_aware_rl/stable-baselines
stack-data                    0.2.0
tensorboard                   1.13.1
tensorboard-data-server       0.6.1
tensorboard-plugin-wit        1.8.1
tensorflow                    1.13.1
tensorflow-estimator          1.13.0
tensorflow-hub                0.1.1
tensorflow-io-gcs-filesystem  0.25.0
tensorflowjs                  0.8.5
termcolor                     1.1.0
terminado                     0.13.3
tf-estimator-nightly          2.8.0.dev2021122109
tinycss2                      1.1.1
tomli                         2.0.1
tornado                       6.1
tqdm                          4.64.0
traitlets                     5.1.1
typing_extensions             4.2.0
urllib3                       1.26.9
wcwidth                       0.2.5
webencodings                  0.5.1
Werkzeug                      2.1.1
wheel                         0.37.1
widgetsnbextension            4.0.0rc0
wrapt                         1.14.0
zipp                          3.8.0
zmq                           0.0.0
