curator实际上并不完美。

【第一个例子】，当一个节点被ctrl+c后，需要经过30秒后leadership才能移交给另一个节点。
我第一个修复的问题就是上述问题发生时(curator-20190908.zip)，为的是leader的切换变得快速。

curator-20190908.zip位于https://github.com/htgithub001/curator-001/releases

