### Choose if you want a programming language from the list:
<details>
<summary><strong>:floppy_disk: Assembly</strong></summary>

```assembly
section .data
    msg db 'Hi there!', 10
    msglen equ $ - msg
section .text
    global _start
_start:
    mov rax, 1
    mov rdi, 1
    mov rsi, msg
    mov rdx, msglen
    syscall
    mov rax, 60
    xor rdi, rdi
    syscall
```
</details>
<details>
<summary><strong>🐚 Bash</strong></summary>

```bash
#!/bin/bash
echo "Hi there!"
```
</details>
<details>
<summary><strong>:gear: C</strong></summary>

```c
#include <stdio.h>
int main(){
  printf("Hi there!\n");
  return 0;
}
```
</details>
<details>
<summary><strong>🛠️ C++</strong></summary>

```cpp
#include <iostream>
using namespace std;
int main(){
  cout<<"Hi there!\n";
  return 0;
}
```
</details>
<details>
<summary><strong>🔷 C#</strong></summary>

```csharp
using System;
class Program{
    static void Main(){
        Console.WriteLine("Hi there!");
    }
}
```
</details>
<details>
<summary><strong>☕ Java</strong></summary>

```java
public class Main{
    public static void main(String[] args){
        System.out.println("Hi there!");
    }
}
```
</details>
<details>
<summary><strong>	🟨 Javascript</strong></summary>

```javascript
console.log("Hi there!");
```
</details>
<details>
<summary><strong>🌙 Lua</strong></summary>

```lua
print("Hi there!")
```
</details>
<details>
<summary><strong>🏛️ Pascal</strong></summary>

```pascal
begin
  writeln('Hi there!');
end.
```
</details>
<details>
<summary><strong>🐍 Python</strong></summary>

```python
print("Hi there!")
```
</details>
<details>
<summary><strong>🦀 Rust</strong></summary>

```rust
fn main(){
    println!("Hi there!");
}
```
</details>

If I'm honest I copied some code from the internet :shipit:.
