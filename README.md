

# GSTCalculator

Calculate Goods and Service tax, Gst rate, Gst Inclusive tax and Gst Exclusive tax




## Installation

Use the CDN to access this package 

```
https://cdn.jsdelivr.net/gh/krish033/GSTCalculator/build.min.js
```
## Usage/Examples
The package provides an object named ``` gst ``` which you can use to calculate taxes

```
gst.Gst(amount, percentage);
```


## Available Methods

#### Example
```javascript
const taxRate = gst.Gst(amount,GSTpercent)
```


#### Methods
| Methods | Parameters    | Description                |
| :-------- | :------- | :------------------------- |
| `Gst` | `taxable`, `taxPercent` | Calculate the tax rate for the given percentage |
| `GstTotal` | `taxable`, `taxPercent` | Calculate the tax rate for the given percentage with taxable added to the return |
| `GstInclusive` | `taxable`, `taxPercent` | Calculate inclusive tax for the given percentage, returns an object |
| `GstExcludes` | `taxable`, `taxPercent` | Calculate Excludes tax rate for the given percentage returns an object |




