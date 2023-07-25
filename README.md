# Digital Clock Made using Flip-Flops and Logic Gates

In this project, we **_designed_** and **_implemented_** a **24-hour clock** using _7-Segment displays, BCD to 7-Segment Decoder ICs, flip-flops and logic gates_. _Arduino Uno R3_ acts as a _1-second clock_ signal generator.

![image](https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/355239da-1dac-457b-81ab-4ff2412e8537)


https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/d61a066d-a101-47c4-9d0f-999da9008ae6


The clock was _designed_ and _simulated_ before implementation on **_Logisim_** software.

![Screenshot 2023-07-25 161734](https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/31913b2d-cfd8-46a1-adfb-f129f606c1ad)

## Subsystemes in the Clock:

**- MOD 6 Counter : _2 nos_
- Clock Input and Power: _1 nos (Arduino)_
- BCD to 7-Segment Decoder: _6 nos_
- MOD 3 Counter: _1 nos_
- MOD 10 Counter: _3 nos_
- 24 - Clock reset: _1 nos_**

![Screenshot 2023-07-25 161745](https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/24c4eb50-7f4e-4aca-b902-c4294f90f620)

## Functions of Some Subsystems:

![Screenshot 2023-07-25 161752](https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/ae86cfc0-cedf-40cf-8191-3a80e9554f1c)

### 1. BCD to 7-Segment:

Even though we ended up using off-the-shelf IC, we have designed **_BCD to 7-Segment_** subsystem ourselves.

![Screenshot 2023-07-25 161800](https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/24ed34cc-e95e-4f4e-abcc-904b9d4b10f2)

![Screenshot 2023-07-25 161816](https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/6e121c84-cdce-49f8-8ec5-ce0a647b80ef)

![Screenshot 2023-07-25 161821](https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/3bc1f0d4-85f3-47eb-8f4b-72c467399641)

**Usage of IC:**

![Screenshot 2023-07-25 161858](https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/7e20bc44-664d-4b78-9f85-9f29cc2c2067)



### 2. MOD 10 Counter:

This counter is used once each in the hours, minutes and seconds section.

![Screenshot 2023-07-25 161827](https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/dc0b8aa6-9676-45c8-b272-252845703df9)


![Screenshot 2023-07-25 161831](https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/6f953acd-1a50-4fef-92e0-2bfa9c569353)

![Screenshot 2023-07-25 161836](https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/3d79d4c9-9757-46c7-8353-d6a8006baffb)

https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/ad8a5d1e-5052-4485-ba31-dc2bb30a3330

### 3. MOD 6 Counter:

This counter is used once each in the minutes and seconds section.

![Screenshot 2023-07-25 161839](https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/3eda5769-466c-477a-a2f1-b20fe3f7e55d)


![Screenshot 2023-07-25 161843](https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/73fe5044-d820-4051-91ae-eaaec22bc789)

![Screenshot 2023-07-25 161846](https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/6770488d-76db-48e5-b44e-4af668437700)

### 4. MOD 3 Counter:

This counter is used in the hours section.

![Screenshot 2023-07-25 161849](https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/c5a3620d-29df-4ec9-8158-24f0ad87cb97)


![Screenshot 2023-07-25 161851](https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/384ddd94-c5bd-4718-8850-84efe346d698)

![Screenshot 2023-07-25 161854](https://github.com/ChiragKotian/digital-clock-using-flipflops-and-logic-gates-/assets/117931123/65242526-41f6-4f45-b086-981749202edf)


## Credits:

_This project was made by [@ChiragKotian](https://www.github.com/ChiragKotian) and [@arpitguptagithub](https://github.com/arpitguptagithub)._




