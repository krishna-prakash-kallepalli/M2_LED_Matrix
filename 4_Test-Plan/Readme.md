# Test Plan


## Obstacle Detection:
### How: Our implementation for this step requires multiple steps :
#### Step 1: Find a distance value between each pair of sensors. To test the distance
value, we may use the numbers we see for the height and length, as well as the
Pythagorean Theorem.
####Step 2: Check the angle found between each pair of sensors using the distance value
initially found.
####Step 3: Using these values, determine what each angle should approximately be to
detect different types of obstacles.
####Step 4: Detect the obstacles.


## Output: As we had steps for each test, we will again make steps for the expected outputs:
#### Step 1: Compare the outputted (through serial) value for the hypotenuse to the
Pythagorean calculated value. We expect them to be the same.
####  Step 2: Using the same technique as step 1 except calculating the angle, we should
see the same value for this calculation as well.
#### Step 3 : The values and outputs for the “obstacle detected” will be constantly
checked and rechecked to make sure the angles determine the correct obstacle.
#### Step4 : Adding Audio to the Ultrasonic Sensors.

## Testing cases

| Average Speed(m/s)                    | 0.8                           | 1.5    | 2.0    |
| ----------------- | -----------------------|-------------|---------|
| Mean RMS error (cm)* | 19.4  |12.7  |10.2|
|SD** |11.2   |14.3  | 13.4|
|Sensing error (%) | 5.0 | 1.6| 1.0|
|----------------------------------------------------------|


#### RMS error : Root mean square error between actual and sensing distance.
#### SD** : Standard deviation of the RMS errors.

# Communication Protocols
## Wired
#### In this project we use UART communication protocol.
### UART  - TX & RX (2 devices)
* 2 Wire
* Individual clocks used by the both parties
* Standard speed (9600, 115200) - Baud rate
* Parity

## Factors to decide on which communication prototocol to select
### * Frequency :
We need 2oKHz frequency for this project because of this UART is suitable for this model.
### * Data throughput
### * Number of pins available :
There are two pins are avaiable.
#### [1] TX (Pin no 3)
#### [2] RX (Pin no 2).
TX and RX pins we need to display our result .

# Output
```bash
Output:1
```
![out1](https://user-images.githubusercontent.com/94118726/144073307-d3856545-054c-4a28-afbb-3cef3479f6b4.JPG)


```bash
Output:2
```

![out2](https://user-images.githubusercontent.com/94118726/144073341-7fb598c1-40ab-4472-9fda-46da9b9ab729.JPG)

```bash
Output:3
```
![out3](https://user-images.githubusercontent.com/94118726/144073364-fbec5d54-7aa8-49b3-8a69-fa51d0d2b5e5.jpg)

