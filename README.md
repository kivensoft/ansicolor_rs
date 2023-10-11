# ansicolor -- terminal ansi color libraty
简单的基于终端的ansi颜色库

---
#### 项目地址
<https://github.com/kivensoft/ansicolor_rs>

###### 技术框架

---
###### 添加依赖
`cargo add --git https://github.com/kivensoft/ansicolor_rs ansicolor`
###### 使用
```rust
use ansicolor;

fn main() {
	println!("这个是{}", ansicolor::ac_red!("红色"));
}
```
