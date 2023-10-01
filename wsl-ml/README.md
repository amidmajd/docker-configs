# ML Jupyter Server with GPU using Docker & VScode 

## Notes

* Add project requirements to `requirements.txt` file
* connect to Jupyter server using `Jupyter Server` from VScode's status bar (when inside a notebook file)
    - Jupyter server address: `http://localhost:8888/?token=token`
    - Select ipython kernel
* to make container's mounted volume writable by user, run this: `chmod a+rwx -R src/`
* For auto completion to work properly in VScode, a few packages should be installed locally (inside wsl and not docker container)
    - `pip install transformers datasets pandas numpy matplotlib seaborn scikit-learn scipy torch torchvision tensorboard lightning nltk`
