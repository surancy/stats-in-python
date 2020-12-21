# Graphical EDA
The histogram using sns.set() default setting had ten bins. This is the default of matplotlib. 
The "square root rule" is a commonly-used rule of thumb for choosing number of bins: choose the number of bins to be the square root of the number of samples. 

```python
n_bins = np.sqrt(len(data))
plt.hist(data,bins = n_bins)
plt.xlabel = ('petal length (cm)') # don't forget the units!
plt.ylabel = ('counts')
```

# Quantitative EDA

# Thinking probabilistically-- Discrete variables

# Thinking probabilistically-- Continuous variables
