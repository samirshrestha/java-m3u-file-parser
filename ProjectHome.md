m3u file parser for java

Usage:
```
try{
  File f = new File("12397709.m3u") // your m3u filename
  M3U_Parser mpt = new M3U_Parser();
  M3UHolder m3hodler = mpt.parseFile(f);
  for (int n = 0; n < m3hodler.getSize(); n++) {
  System.out.println(m3hodler.getName(n));
  System.out.println(m3hodler.getUrl(n));
  }
}catch(Exception e){
  e.printStackTrace():
}


```