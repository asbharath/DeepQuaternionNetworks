# DeepQuaternionNetworks
Paper and code for the paper Deep Quaternion Networks https://arxiv.org/abs/1712.04604

## Installation 

```
make build
make run
```

```python
# shallow
python runner.py classification --mode quaternion -nb 2 -sf 8 -bs 64

# deep
python runner.py classification --mode quaternion -nb 10 -sf 8 -bs 64
```


The paper has been accepted to IJCNN 2018.

Please feel free to email me with questions about using the code. I will be making documentation changes and cleaning up the code as soon as I have some more spare time.


If using this code or work presented in the paper please cite

@article{gaudet2017deep,

  title={Deep Quaternion Networks},
  
  author={Gaudet, Chase and Maida, Anthony},
  
  journal={arXiv preprint arXiv:1712.04604},
  
  year={2017}
  
}
