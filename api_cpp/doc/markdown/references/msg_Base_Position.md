# Message Position

This page describes the C++ Kinova::Api::Base::Position message.

## Overview / Purpose

Defines a Cartesian position

## Class members

 **Member variables** 

|Member name|Data type|Description|
|-----------|---------|-----------|
|x|float32|X position \(in meters\)|
|y|float32|Y position \(in meters\)|
|z|float32|Z position \(in meters\)|

 **Methods** 

The methods listed below are some of the most commonly used. Please refer to Google Protocol Buffer documentation for an exhaustive list.

|Method name|Return type|Input type|Description|
|-----------|-----------|----------|-----------|
|x\(\)|float32|void|Returns the current value of x. If the x is not set, returns 0.|
|set\_x\(\)|void|float32|Sets the value of x. After calling this, x\(\) will return value.|
|clear\_x\(\)|void|void|Clears the value of x. After calling this, x\(\) will return 0.|
|y\(\)|float32|void|Returns the current value of y. If the y is not set, returns 0.|
|set\_y\(\)|void|float32|Sets the value of y. After calling this, y\(\) will return value.|
|clear\_y\(\)|void|void|Clears the value of y. After calling this, y\(\) will return 0.|
|z\(\)|float32|void|Returns the current value of z. If the z is not set, returns 0.|
|set\_z\(\)|void|float32|Sets the value of z. After calling this, z\(\) will return value.|
|clear\_z\(\)|void|void|Clears the value of z. After calling this, z\(\) will return 0.|

**Parent topic:** [Base](../references/summary_Base.md)

