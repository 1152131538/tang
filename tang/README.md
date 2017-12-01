public static void write() throws IOException
  {
  OutputStreamWriter osw1 = new OutputStreamWriter(new FileOutputStream("gbk.txt"),"GBK");
  osw1.write("ÄãºÃ");
  osw1.close();
  
  OutputStreamWriter osw2 = new OutputStreamWriter(new FileOutputStream("utf-8.txt"),"UTF-8");
  osw2.write("ÄãºÃ");
  osw2.close();
 }
 public static void read() throws IOException
 {
 InputStreamReader isr = new InputStreamReader(new FileInputStream("gbk.txt"),"GBK");
 byte[] buf = new byte[1024];
 int len = isr.read(buf);
 sop(new String(buf,0,len));
 }
ghjhgjhjhjjh




公元1695年他接他爹的班，考不取功名的结果是接手自家酒馆。
又听说同乡谁已经入京做上小官，他的梦，来往客谁能买单？
