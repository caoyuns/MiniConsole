�÷���
final MiniConsole console = new MiniConsole("MiniConsole Test");
console.start();

console.setInputHandler(new InputHandler() {
	
	@Override
	public void onLineInput(String arg0) {
		// TODO Auto-generated method stub
		console.println(arg0);
	}
});

��ݼ���
�س�   ����
����   ��ʾ��ʷ����
Ctrl+L ������
