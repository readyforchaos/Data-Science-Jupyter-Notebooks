#### How to use:
```python
print("pip install scriptedforms")
print("in terminal: scriptedforms filename.md")
```

#### Slider for matplotlib chart

Check this slider:

<section-start onLoad>

</section-start>

<section-live>

<variable-slider label="Slider 1" min="0" max="6" step="1">omega[0]</variable-slider>

```python
plt.figure(figsize=(5*1.618,5))

    
x = [1,5]
y = [1,5]
sumz = 1337
    
plt.plot(x,(y+omega[0]))


plt.xlim([1, 6])
plt.ylim([1, 6])
plt.title('Test')
plt.legend([r'{0:0.1f}'.format(omega[0])], loc='upper right')
plt.xlabel('something X')
plt.ylabel('something Y');
```

</section-live>