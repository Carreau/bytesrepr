# BytesRepr

Change the `__rerp__` of bytes in IPython (python 3) to look less like text:


```python
In[1]: import bytesrepr
In[2]: bytesrerpr.enable()
In[3]: b'These are bytes'
<bytes b'These are bytes' at 0x107e0c000>
```


Bytes will be elided to `...`in the rerp if too long.



