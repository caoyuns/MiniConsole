用法：

ss

final MiniConsole console = new MiniConsole("MiniConsole Test");
console.start();

console.setInputHandler(new InputHandler() {
	
	@Override
	public void onLineInput(String arg0) {
		// TODO Auto-generated method stub
		console.println(arg0);
	}
});

快捷键：
回车   输入
上下   显示历史命令
Ctrl+L 清空输出

