������githubһЩ�򵥵Ĳ�����
1������ע��һ��github���˻�
2���ڵ����ϰ�װgit����
3������git��github�������߹���������
1�� Linux �� Mac ����Ĭ�ϰ�װ�� SSH ���� Windows ϵͳ��װ�� Git Bash Ӧ��Ҳ�Ǵ�SSH�ģ���ҿ������նˣ�win���� Git Bash ����� ssh �鿴�Ƿ��Ѿ���װ��ssh����װ�ɹ���ʾ���£�

     ���������� ssh-keygen -t rsa ��ʲô��˼�أ�����ָ�� rsa �㷨������Կ���������������س���������Ҫ�������룩��Ȼ��ͻ����������ļ� id_rsa �� id_rsa.pub ���� id_rsa ����Կ��id_rsa.pub ���ǹ�Կ�������ļ�Ĭ�Ϸֱ�������Ŀ¼�����ɣ� Linux/Mac ϵͳ �� ~/.ssh �£�winϵͳ�� /c/Documents and Settings/username/.ssh �£����������ļ������������а취�鿴��������Ҫ�����ǰ� id_rsa.pub ��������ӵ� GitHub �ϣ������㱾�ص� id_rsa ��Կ�� GitHub �ϵ� id_rsa.pub ��Կ������ԣ���Ȩ�ɹ��ſ����ύ���롣
2�� ��һ������ GitHub �ϵ�����ҳ�棬�������� SSH and GPG keys��



     �ڶ���Ȼ�������Ͻǵ� New SSH key ��ť��
     
     ��Ҫ����ֻ���� Key ������ id_rsa.pub ��Կ�ļ�������ݸ���ճ����ȥ�Ϳ����ˣ�����ʾ��Ϊ�˰�ȫճ���Ĺ�Կ����Ч�ģ���Title ��������Ҫ��д����� Add SSH key ��ť��ok�ˡ�SSH key ��ӳɹ�֮������ ssh -T git@github.com ���в��ԣ������Ƿ���ӳɹ���
 3��clone github�ϵĴ��룬 git clone git@github.com:stormzhang/test.git 
    ��git clone git@github.com:zhlmgithub/okhttp.git��������������clone�ô���֮�󣬾Ϳ�����git���������Ĳ����ˡ�

