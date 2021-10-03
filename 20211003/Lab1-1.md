# 1-1 在TinkerCAD開一個新的Circuit, 加上一個外部的LED, 並且ON (亮) 1秒, OFF(滅) 1秒

## 電路
![image](https://user-images.githubusercontent.com/89304181/133880225-ccf34552-9449-4753-9cbf-4d941ed1f31f.png)



## 程式
![image](https://user-images.githubusercontent.com/89304181/133880248-a1e54182-8659-4717-9853-25940498bd7e.png)


````C
void setup()
{
  pinMode(13, OUTPUT);
}

void loop()
{
  // turn the LED on (HIGH is the voltage level)
  digitalWrite(LED_BUILTIN, HIGH);
  delay(500); // Wait for 500 millisecond(s)
  // turn the LED off by making the voltage LOW
  digitalWrite(LED_BUILTIN, LOW);
  delay(500); // Wait for 500 millisecond(s)
}

````