       
<div class="blog_main">
  <div class="blog_title">
    <h3>
      <a href="/blog/1770014">Apache Commons工具集简介</a>
      <em class="actions">      </em>
    </h3>
    <ul class='blog_categories'><strong>博客分类：</strong> <li><a href="/category/232189">java</a></li> </ul>
        <div class='news_tag'><a href="http://www.iteye.com/blogs/tag/apache">apache</a><a href="http://www.iteye.com/blogs/tag/commons">commons</a><a href="http://www.iteye.com/blogs/tag/java">java</a><a href="http://www.iteye.com/blogs/tag/bean">bean</a><a href="http://www.iteye.com/blogs/tag/jdbc">jdbc</a>&nbsp;</div>
  </div>

  <div id="blog_content" class="blog_content">
    <div class="iteye-blog-content-contain" style="font-size: 14px;">
<p><span style="font-size: small;">        <span>Apache Commons包含了很多开源的工具，用于解决平时编程经常会遇到的问题，减少重复劳动。下面是我这几年做开发过程中</span></span><span style="font-size: small;"><span><span style="font-size: small;"><span>自</span></span>己<span style="font-size: small;">用过的</span>工具类做简单介绍。</span> </span></p>
<p> </p>
<table class="bodyTable" border="0" style="width: 706px; height: 565px;">
<tr class="b">
<td style="font-family: Verdana,Helvetica,Arial,sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #32bdcd; color: #000000; padding: 2px 4px;"><strong><span style="color: #000000;">组件</span></strong></td>
<td style="font-family: Verdana,Helvetica,Arial,sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #32bdcd; color: #000000; padding: 2px 4px;"><strong><span style="color: #000000; font-family: SimSun,宋体,tahoma,arial,helvetica,sans-serif;">功能介绍</span></strong></td>
</tr>
<tr class="b">
<td style="font-family: Verdana,Helvetica,Arial,sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #dddddd; color: #000000; padding: 2px 4px;"><span style="text-decoration: underline; color: #0000ff;">BeanUtils</span></td>
<td style="font-family: Verdana,Helvetica,Arial,sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #dddddd; color: #000000; padding: 2px 4px;">
<span style="font-size: small;"><span>提供了对于JavaBean进行各种操作，克隆对象,属性等等</span></span>.</td>
</tr>
<tr class="a">
<td style="font-family: Verdana,Helvetica,Arial,sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #efefef; color: #000000; padding: 2px 4px;"><span style="text-decoration: underline; color: #0000ff;">Betwixt</span></td>
<td style="font-family: Verdana,Helvetica,Arial,sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #efefef; color: #000000; padding: 2px 4px;">
<span style="font-size: small;"><span>XML与Java对象之间相互转换</span></span>.</td>
</tr>
<tr class="a">
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #dddddd; color: #000000; padding: 2px 4px;"><span style="text-decoration: underline; color: #0000ff;">Codec</span></td>
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #dddddd; color: #000000; padding: 2px 4px;">
<span><span style="font-size: small;"><span style="font-style: normal; font-variant: normal; font-weight: normal; letter-spacing: normal; line-height: 18px; text-align: start; text-indent: 0px; white-space: normal; display: inline ! important; float: none; font-family: arial; color: #000000;">处理常用的编码方法的工具类包 </span> </span> </span> <span><span style="font-size: small;"><span style="font-style: normal; font-variant: normal; font-weight: normal; letter-spacing: normal; line-height: 18px; text-align: start; text-indent: 0px; white-space: normal; display: inline ! important; float: none; font-family: arial; color: #000000;"><span style="font-style: normal; font-variant: normal; font-weight: normal; letter-spacing: normal; line-height: 18px; text-align: start; text-indent: 0px; white-space: normal; display: inline ! important; float: none; font-family: arial; color: #000000;">例如DES、SHA1、MD5、Base64等</span></span></span></span>.</td>
</tr>
<tr class="b">
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #efefef; color: #000000; padding: 2px 4px;"><span style="text-decoration: underline; color: #0000ff;">Collections</span></td>
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #efefef; color: #000000; padding: 2px 4px;">
<span style="font-size: small;">java集合框架操作</span>.</td>
</tr>
<tr class="a">
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #dddddd; color: #000000; padding: 2px 4px;"><span style="text-decoration: underline; color: #0000ff;">Compress</span></td>
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #dddddd; color: #000000; padding: 2px 4px;">
<span style="font-size: small;"><span>java提供文件打包 压缩类库</span></span>.</td>
</tr>
<tr class="b">
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #efefef; color: #000000; padding: 2px 4px;"><span style="text-decoration: underline; color: #0000ff;">Configuration</span></td>
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #efefef; color: #000000; padding: 2px 4px;">
<span><span style="font-style: normal; font-variant: normal; font-weight: normal; letter-spacing: normal; line-height: 18px; text-align: start; text-indent: 0px; white-space: normal; display: inline ! important; float: none; font-family: arial; color: #000000; font-size: small;">一个java应用程序的配置管理类库</span></span>.</td>
</tr>
<tr class="a">
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #dddddd; color: #000000; padding: 2px 4px;"><span style="text-decoration: underline; color: #0000ff;">DBCP</span></td>
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #dddddd; color: #000000; padding: 2px 4px;">
<span style="font-size: small;">提供数据库连接池服务</span>.</td>
</tr>
<tr class="b">
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #efefef; color: #000000; padding: 2px 4px;"><span style="text-decoration: underline; color: #0000ff;">DbUtils</span></td>
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #efefef; color: #000000; padding: 2px 4px;">
<span><span>提供<span style="font-size: small;">对jdbc</span> </span> 的操作封装来简化数据查询和记录读取操作</span>.</td>
</tr>
<tr class="b">
<td style="font-family: Verdana,Helvetica,Arial,sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #dddddd; color: #000000; padding: 2px 4px;"><span style="text-decoration: underline; color: #0000ff;">Email</span></td>
<td style="font-family: Verdana,Helvetica,Arial,sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #dddddd; color: #000000; padding: 2px 4px;">
<span style="font-size: small;"><span>java发送邮件 对javamail的封装</span></span>.</td>
</tr>
<tr class="b">
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #efefef; color: #000000; padding: 2px 4px;"><span style="text-decoration: underline; color: #0000ff;">FileUpload</span></td>
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #efefef; color: #000000; padding: 2px 4px;">
<span style="font-size: small;">提供文件上传功能</span>.</td>
</tr>
<tr class="a">
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #dddddd; color: #000000; padding: 2px 4px;"><span style="text-decoration: underline; color: #0000ff;">HttpClien</span></td>
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #dddddd; color: #000000; padding: 2px 4px;"><span style="font-size: small;">提供HTTP客户端与服务器的各种通讯操作. 现在已改成HttpComponents<br></span></td>
</tr>
<tr class="a">
<td style="font-family: Verdana,Helvetica,Arial,sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #efefef; color: #000000; padding: 2px 4px;"><span style="text-decoration: underline; color: #0000ff;">IO</span></td>
<td style="font-family: Verdana,Helvetica,Arial,sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #efefef; color: #000000; padding: 2px 4px;">
<span style="font-size: small;">io工具的封装</span>.</td>
</tr>
<tr class="a">
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #dddddd; color: #000000; padding: 2px 4px;"><span style="text-decoration: underline; color: #0000ff;">Lang</span></td>
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #dddddd; color: #000000; padding: 2px 4px;">
<span><span style="font-size: small;"><span style="font-style: normal; font-variant: normal; font-weight: normal; letter-spacing: normal; line-height: 18px; text-align: start; text-indent: 0px; white-space: normal; display: inline ! important; float: none; font-family: arial; color: #000000;">Java基本对象方法的工具类包 如：StringUtils,ArrayUtils等等</span></span></span>.</td>
</tr>
<tr class="a">
<td style="font-family: Verdana,Helvetica,Arial,sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #efefef; color: #000000; padding: 2px 4px;"><span style="text-decoration: underline; color: #0000ff;">Logging</span></td>
<td style="font-family: Verdana,Helvetica,Arial,sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #efefef; color: #000000; padding: 2px 4px;">
<span style="font-size: small;"><span>提供的是一个Java 的日志接口</span></span>.</td>
</tr>
<tr class="b">
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #efefef; color: #000000; padding: 2px 4px;"><span style="text-decoration: underline; color: #0000ff;">Validator</span></td>
<td style="border: none; font-family: Verdana, Helvetica, Arial, sans-serif; font-size: small; text-align: left; vertical-align: top; background-color: #efefef; color: #000000; padding: 2px 4px;">
<span style="font-size: small;"><span><span style="font-style: normal; font-variant: normal; font-weight: normal; letter-spacing: normal; line-height: 18px; text-align: start; text-indent: 0px; white-space: normal; display: inline ! important; float: none; font-family: arial; color: #000000; font-size: small;">提供了客户端和服务器端的数据验证框架</span></span></span>.</td>
</tr>
</table>
</div>
<p> </p>
<p><strong>1、BeanUtils</strong> 提供了对于JavaBean进行各种操作， 比如对象,属性复制等等。</p>
<p> </p>
<pre class="java" name="code">//1、 克隆对象
//	新创建一个普通Java Bean，用来作为被克隆的对象

	public class Person {
	private String name = "";
	private String email = "";

	private int age;
	//省略 set,get方法
	}

//	再创建一个Test类，其中在main方法中代码如下：
	import java.lang.reflect.InvocationTargetException;
	import java.util.HashMap;
	import java.util.Map;
	import org.apache.commons.beanutils.BeanUtils;
	import org.apache.commons.beanutils.ConvertUtils;
	public class Test {

	/**

	* @param args

	*/
	public static void main(String[] args) {
	Person person = new Person();
	person.setName("tom");
	person.setAge(21);
	try {
	        //克隆
		Person person2 =  (Person)BeanUtils.cloneBean(person);
		System.out.println(person2.getName()+"&gt;&gt;"+person2.getAge());
	} catch (IllegalAccessException e) {
		e.printStackTrace();
	} catch (InstantiationException e) {
		e.printStackTrace();
	} catch (InvocationTargetException e) {
		e.printStackTrace();
	} catch (NoSuchMethodException e) {
		e.printStackTrace();

	}

	}

	}

//	原理也是通过Java的反射机制来做的。
//	2、 将一个Map对象转化为一个Bean
//	这个Map对象的key必须与Bean的属性相对应。
	Map map = new HashMap();
	map.put("name","tom");
	map.put("email","tom@");
	map.put("age","21");
	//将map转化为一个Person对象
	Person person = new Person();
	BeanUtils.populate(person,map);
//	通过上面的一行代码，此时person的属性就已经具有了上面所赋的值了。
//  将一个Bean转化为一个Map对象了，如下：
    Map map = BeanUtils.describe(person)</pre>
<p> </p>
<p><strong>2、Betwixt  </strong>XML与Java对象之间相互转换。<strong><br></strong></p>
<p> </p>
<pre class="java" name="code">//1、 将JavaBean转为XML内容
	// 新创建一个Person类
	public class Person{
		private String name;
		private int age;
		/** Need to allow bean to be created via reflection */
		public PersonBean() {
		}
		public PersonBean(String name, int age) {
			this.name = name;
			this.age = age;
		}
		//省略set, get方法
		public String toString() {
			return "PersonBean[name='" + name + "',age='" + age + "']";
		}
	}
	
	//再创建一个WriteApp类：
	import java.io.StringWriter;
	import org.apache.commons.betwixt.io.BeanWriter;
	public class WriteApp {
	/**
	* 创建一个例子Bean，并将它转化为XML.
	*/
	public static final void main(String [] args) throws Exception {
		// 先创建一个StringWriter，我们将把它写入为一个字符串       
		StringWriter outputWriter = new StringWriter();
		// Betwixt在这里仅仅是将Bean写入为一个片断
		// 所以如果要想完整的XML内容，我们应该写入头格式
		outputWriter.write(“&lt;?xml version=’1.0′ encoding=’UTF-8′ ?&gt;\n”);
		// 创建一个BeanWriter，其将写入到我们预备的stream中
		BeanWriter beanWriter = new BeanWriter(outputWriter);
		// 配置betwixt
		// 更多详情请参考java docs 或最新的文档
		beanWriter.getXMLIntrospector().getConfiguration().setAttributesForPrimitives(false);
		beanWriter.getBindingConfiguration().setMapIDs(false);
		beanWriter.enablePrettyPrint();
		// 如果这个地方不传入XML的根节点名，Betwixt将自己猜测是什么
		// 但是让我们将例子Bean名作为根节点吧
		beanWriter.write(“person”, new PersonBean(“John Smith”, 21));
		//输出结果
		System.out.println(outputWriter.toString());
		// Betwixt写的是片断而不是一个文档，所以不要自动的关闭掉writers或者streams，
		//但这里仅仅是一个例子，不会做更多事情，所以可以关掉
		outputWriter.close();
		}
	}
//2、 将XML转化为JavaBean
	import java.io.StringReader;
	import org.apache.commons.betwixt.io.BeanReader;
	public class ReadApp {
	public static final void main(String args[]) throws Exception{
		// 先创建一个XML，由于这里仅是作为例子，所以我们硬编码了一段XML内容
		StringReader xmlReader = new StringReader(
		"&lt;?xml version=’1.0′ encoding=’UTF-8′ ?&gt; &lt;person&gt;&lt;age&gt;25&lt;/age&gt;&lt;name&gt;James Smith&lt;/name&gt;&lt;/person&gt;");
		//创建BeanReader
		BeanReader beanReader  = new BeanReader();
		//配置reader
		beanReader.getXMLIntrospector().getConfiguration().setAttributesForPrimitives(false);
		beanReader.getBindingConfiguration().setMapIDs(false);
		//注册beans，以便betwixt知道XML将要被转化为一个什么Bean
		beanReader.registerBeanClass("person", PersonBean.class);
		//现在我们对XML进行解析
		PersonBean person = (PersonBean) beanReader.parse(xmlReader);
		//输出结果
		System.out.println(person);
		}
	}</pre>
<p> </p>
<p><strong>3、Codec</strong> 提供了一些公共的编解码实现，比如Base64, Hex, MD5,Phonetic and URLs等等。</p>
<p> </p>
<pre class="java" name="code">//Base64编解码
private static String encodeTest(String str){
		Base64 base64 = new Base64();
		try {
			str = base64.encodeToString(str.getBytes("UTF-8"));
		} catch (UnsupportedEncodingException e) {
			e.printStackTrace();
		}
			System.out.println("Base64 编码后："+str);
		return str;
	}

	private static void decodeTest(String str){
		Base64 base64 = new Base64();
		//str = Arrays.toString(Base64.decodeBase64(str));
		str = new String(Base64.decodeBase64(str));
		System.out.println("Base64 解码后："+str);
	}</pre>
<p> </p>
<p><strong>4、Collections </strong>对java.util的扩展封装，处理数据还是挺灵活的。<strong><br></strong></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span style="color: #0000ff;"><span style="font-family: 'Trebuchet MS';">org.apache.commons.collections – Commons Collections</span><span style="font-family: 宋体;">自定义的一组公用的接口和工具类</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span style="color: #0000ff;"><span style="font-family: 'Trebuchet MS';">org.apache.commons.collections.bag – </span><span style="font-family: 宋体;">实现</span><span style="font-family: 'Trebuchet MS';">Bag</span><span style="font-family: 宋体;">接口的一组类</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span style="color: #0000ff;"><span style="font-family: 'Trebuchet MS';">org.apache.commons.collections.bidimap – </span><span style="font-family: 宋体;">实现</span><span style="font-family: 'Trebuchet MS';">BidiMap</span><span style="font-family: 宋体;">系列接口的一组类</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span style="color: #0000ff;"><span style="font-family: 'Trebuchet MS';">org.apache.commons.collections.buffer – </span><span style="font-family: 宋体;">实现</span><span style="font-family: 'Trebuchet MS';">Buffer</span><span style="font-family: 宋体;">接口的一组类</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span style="color: #0000ff;"><span style="font-family: 'Trebuchet MS';">org.apache.commons.collections.collection – </span><span style="font-family: 宋体;">实现</span><span style="font-family: 'Trebuchet MS';">java.util.Collection</span><span style="font-family: 宋体;">接口的一组类</span></span></p>
<p><span style="color: #0000ff;"><span style="font-family: 'Trebuchet MS';">org.apache.commons.collections.comparators – </span><span style="font-family: 宋体;">实现</span><span style="font-family: 'Trebuchet MS';">java.util.Comparator</span><span style="font-family: 宋体;">接口的一组类</span> </span></p>
<p><span style="color: #0000ff;"><span style="font-family: 'Trebuchet MS';">org.apache.commons.collections.functors – Commons Collections</span><span style="font-family: 宋体;">自定义的一组功能类</span> </span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span style="color: #0000ff;"><span style="font-family: 'Trebuchet MS';">org.apache.commons.collections.iterators – </span><span style="font-family: 宋体;">实现</span><span style="font-family: 'Trebuchet MS';">java.util.Iterator</span><span style="font-family: 宋体;">接口的一组类</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span style="color: #0000ff;"><span style="font-family: 'Trebuchet MS';">org.apache.commons.collections.keyvalue – </span><span style="font-family: 宋体;">实现集合和键</span><span style="font-family: 'Trebuchet MS';">/</span><span style="font-family: 宋体;">值映射相关的一组类</span></span></p>
<p><span style="color: #0000ff;"><span style="font-family: 'Trebuchet MS';">org.apache.commons.collections.list – </span><span style="font-family: 宋体;">实现</span><span style="font-family: 'Trebuchet MS';">java.util.List</span><span style="font-family: 宋体;">接口的一组类</span> </span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span style="color: #0000ff;"><span style="font-family: 'Trebuchet MS';">org.apache.commons.collections.map – </span><span style="font-family: 宋体;">实现</span><span style="font-family: 'Trebuchet MS';">Map</span><span style="font-family: 宋体;">系列接口的一组类</span></span></p>
<p><span style="color: #0000ff;"><span style="font-family: 'Trebuchet MS';">org.apache.commons.collections.set – </span><span style="font-family: 宋体;">实现</span><span style="font-family: 'Trebuchet MS';">Set</span><span style="font-family: 宋体;">系列接口的一组类</span></span></p>
<pre class="java" name="code">/**
		* 得到集合里按顺序存放的key之后的某一Key
		*/
		OrderedMap map = new LinkedMap();
		map.put("FIVE", "5");
		map.put("SIX", "6");
		map.put("SEVEN", "7");
		map.firstKey(); // returns "FIVE"
		map.nextKey("FIVE"); // returns "SIX"
		map.nextKey("SIX"); // returns "SEVEN" 
	
		/**
		* 通过key得到value
		* 通过value得到key
		* 将map里的key和value对调
		*/
	
		BidiMap bidi = new TreeBidiMap();
		bidi.put("SIX", "6");
		bidi.get("SIX");  // returns "6"
		bidi.getKey("6");  // returns "SIX"
		//	     bidi.removeValue("6");  // removes the mapping
		BidiMap inverse = bidi.inverseBidiMap();  // returns a map with keys and values swapped
		System.out.println(inverse);

		/**
		 * 得到两个集合中相同的元素
		 */
		List&lt;String&gt; list1 = new ArrayList&lt;String&gt;();
		list1.add("1");
		list1.add("2");
		list1.add("3");
		List&lt;String&gt; list2 = new ArrayList&lt;String&gt;();
		list2.add("2");
		list2.add("3");
		list2.add("5");
		Collection c = CollectionUtils.retainAll(list1, list2);
		System.out.println(c);</pre>
<p> </p>
<p><strong>5、Compress </strong>commons compress中的打包、压缩类库。<strong> <br></strong></p>
<p> </p>
<pre class="java" name="code">//创建压缩对象
	ZipArchiveEntry entry = new ZipArchiveEntry("CompressTest");
	  //要压缩的文件
	  File f=new File("e:\\test.pdf");
	  FileInputStream fis=new FileInputStream(f);
	  //输出的对象 压缩的文件
	  ZipArchiveOutputStream zipOutput=new ZipArchiveOutputStream(new File("e:\\test.zip"));  
	  zipOutput.putArchiveEntry(entry);
	  int i=0,j;
	  while((j=fis.read()) != -1)
	  { 
	   zipOutput.write(j);
	   i++;
	   System.out.println(i);
	  }
	  zipOutput.closeArchiveEntry();
	  zipOutput.close();
	  fis.close();</pre>
<p> </p>
<p> </p>
<p><strong>6、Configuration</strong> 用来帮助处理配置文件的，支持很多种存储方式。<br>1. Properties files<br>2. XML documents<br>3. Property list files (.plist)<br>4. JNDI<br>5. JDBC Datasource<br>6. System properties<br>7. Applet parameters<br>8. Servlet parameters</p>
<pre class="java" name="code">//举一个Properties的简单例子
# usergui.properties
colors.background = #FFFFFF
colors.foreground = #000080
window.width = 500
window.height = 300

PropertiesConfiguration config = new PropertiesConfiguration("usergui.properties");
config.setProperty("colors.background", "#000000);
config.save();

config.save("usergui.backup.properties);//save a copy
Integer integer = config.getInteger("window.width");</pre>
<p> </p>
<p><strong>7、DBCP</strong><em>  </em>(Database Connection Pool)是一个依赖Jakarta commons-pool对象池机制的数据库连接池,Tomcat的数据源使用的就是DBCP。</p>
<pre class="java" name="code">import javax.sql.DataSource;
import java.sql.Connection;
import java.sql.Statement;
import java.sql.ResultSet;
import java.sql.SQLException;

import org.apache.commons.pool.ObjectPool;
import org.apache.commons.pool.impl.GenericObjectPool;
import org.apache.commons.dbcp.ConnectionFactory;
import org.apache.commons.dbcp.PoolingDataSource;
import org.apache.commons.dbcp.PoolableConnectionFactory;
import org.apache.commons.dbcp.DriverManagerConnectionFactory;
//官方示例
public class PoolingDataSources {

	public static void main(String[] args) {
	 	System.out.println("加载jdbc驱动");
	 	try {
	 	Class.forName("oracle.jdbc.driver.OracleDriver");
	 	} catch (ClassNotFoundException e) {
	 	e.printStackTrace();
	 	}
	 	System.out.println("Done.");
	 	//
	 	System.out.println("设置数据源");
	 	DataSource dataSource = setupDataSource("jdbc:oracle:thin:@localhost:1521:test");
	 	System.out.println("Done.");
	 	
	 	//
	 	Connection conn = null;
	 	Statement stmt = null;
	 	ResultSet rset = null;
	 	
	 	try {
	 	System.out.println("Creating connection.");
	 	conn = dataSource.getConnection();
	 	System.out.println("Creating statement.");
	 	stmt = conn.createStatement();
	 	System.out.println("Executing statement.");
	 	rset = stmt.executeQuery("select * from person");
	 	System.out.println("Results:");
	 	int numcols = rset.getMetaData().getColumnCount();
	 	while(rset.next()) {
	 	for(int i=0;i&lt;=numcols;i++) {
	 	System.out.print("\t" + rset.getString(i));
	 	}
	 	System.out.println("");
	 	}
	 	} catch(SQLException e) {
	 	e.printStackTrace();
	 	} finally {
	 	try { if (rset != null) rset.close(); } catch(Exception e) { }
	 	try { if (stmt != null) stmt.close(); } catch(Exception e) { }
	 	try { if (conn != null) conn.close(); } catch(Exception e) { }
	 	}
	 	}

	public static DataSource setupDataSource(String connectURI) {
		//设置连接地址
		ConnectionFactory connectionFactory = new DriverManagerConnectionFactory(
				connectURI, null);

		// 创建连接工厂
		PoolableConnectionFactory poolableConnectionFactory = new PoolableConnectionFactory(
				connectionFactory);

		//获取GenericObjectPool 连接的实例
		ObjectPool connectionPool = new GenericObjectPool(
				poolableConnectionFactory);

		// 创建 PoolingDriver
		PoolingDataSource dataSource = new PoolingDataSource(connectionPool);
		
		return dataSource;
	}
}</pre>
<p> </p>
<p><strong>8、DbUtils </strong>Apache组织提供的一个资源JDBC工具类库，它是对JDBC的简单封装，<span style="color: #000000;">对传统操作数据库的类进行二次封装，可以把结果集转化成List。</span>，同时也不影响程序的性能。<strong><br></strong></p>
<p><span style="color: #0000ff;">DbUtils类：启动类</span><br><span style="color: #0000ff;">ResultSetHandler接口：转换类型接口</span><br><span style="color: #0000ff;">MapListHandler类：实现类，把记录转化成List</span><br><span style="color: #0000ff;">BeanListHandler类：实现类，把记录转化成List，使记录为JavaBean类型的对象</span><br><span style="color: #0000ff;">Qrery Runner类：执行SQL语句的类</span></p>
<pre class="java" name="code">import org.apache.commons.dbutils.DbUtils;
import org.apache.commons.dbutils.QueryRunner;
import org.apache.commons.dbutils.handlers.BeanListHandler;
import java.sql.Connection;
import java.sql.DriverManager;
import java.sql.SQLException;
import java.util.List;
//转换成list
public class BeanLists {
    public static void main(String[] args) {
        Connection conn = null;
        String url = "jdbc:mysql://localhost:3306/ptest";
        String jdbcDriver = "com.mysql.jdbc.Driver";
        String user = "root";
        String password = "ptest";

        DbUtils.loadDriver(jdbcDriver);
        try {
            conn = DriverManager.getConnection(url, user, password);
            QueryRunner qr = new QueryRunner();
            List results = (List) qr.query(conn, "select id,name from person", new BeanListHandler(Person.class));
            for (int i = 0; i &lt; results.size(); i++) {
                Person p = (Person) results.get(i);
                System.out.println("id:" + p.getId() + ",name:" + p.getName());
            }
        } catch (SQLException e) {
            e.printStackTrace();
        } finally {
            DbUtils.closeQuietly(conn);
        }
    }
}

public class Person{
    private Integer id;
    private String name;

   //省略set, get方法
}

import org.apache.commons.dbutils.DbUtils;
import org.apache.commons.dbutils.QueryRunner;
import org.apache.commons.dbutils.handlers.MapListHandler;

import java.sql.Connection;
import java.sql.DriverManager;
import java.sql.SQLException;

import java.util.List;
import java.util.Map;
//转换成map
public class MapLists {
    public static void main(String[] args) {
        Connection conn = null;
        String url = "jdbc:mysql://localhost:3306/ptest";
        String jdbcDriver = "com.mysql.jdbc.Driver";
        String user = "root";
        String password = "ptest";

        DbUtils.loadDriver(jdbcDriver);
        try {
            conn = DriverManager.getConnection(url, user, password);
            QueryRunner qr = new QueryRunner();
            List results = (List) qr.query(conn, "select id,name from person", new MapListHandler());
            for (int i = 0; i &lt; results.size(); i++) {
                Map map = (Map) results.get(i);
                System.out.println("id:" + map.get("id") + ",name:" + map.get("name"));
            }
        } catch (SQLException e) {
            e.printStackTrace();
        } finally {
            DbUtils.closeQuietly(conn);
        }
    }
}</pre>
<p> </p>
<p><strong>9、Email </strong><span style="font-size: 14px;">提供的一个开源的API，是对javamail的封装。</span></p>
<p> </p>
<pre class="java" name="code">//用commons email发送邮件
public static void main(String args[]){
		Email email = new SimpleEmail();
		email.setHostName("smtp.googlemail.com");
		email.setSmtpPort(465);
		email.setAuthenticator(new DefaultAuthenticator("username", "password"));
		email.setSSLOnConnect(true);
		email.setFrom("user@gmail.com");
		email.setSubject("TestMail");
		email.setMsg("This is a test mail ... :-)");
		email.addTo("foo@bar.com");
		email.send();
	}</pre>
<p> </p>
<p><strong>10、FileUpload </strong><span style="font-size: 14px;">java web文件上传功能。<strong><br></strong></span></p>
<pre class="java" name="code">//官方示例：
//* 检查请求是否含有上传文件
	// Check that we have a file upload request
	boolean isMultipart = ServletFileUpload.isMultipartContent(request);

	//现在我们得到了items的列表

	//如果你的应用近于最简单的情况，上面的处理就够了。但我们有时候还是需要更多的控制。
	//下面提供了几种控制选择：
	// Create a factory for disk-based file items
	DiskFileItemFactory factory = new DiskFileItemFactory();

	// Set factory constraints
	factory.setSizeThreshold(yourMaxMemorySize);
	factory.setRepository(yourTempDirectory);

	// Create a new file upload handler
	ServletFileUpload upload = new ServletFileUpload(factory);

	// 设置最大上传大小
	upload.setSizeMax(yourMaxRequestSize);

	// 解析所有请求
	List /* FileItem */ items = upload.parseRequest(request);

	// Create a factory for disk-based file items
	DiskFileItemFactory factory = new DiskFileItemFactory(
	        yourMaxMemorySize, yourTempDirectory);

	//一旦解析完成，你需要进一步处理item的列表。
	// Process the uploaded items
	Iterator iter = items.iterator();
	while (iter.hasNext()) {
	    FileItem item = (FileItem) iter.next();

	    if (item.isFormField()) {
	        processFormField(item);
	    } else {
	        processUploadedFile(item);
	    }
	}

	//区分数据是否为简单的表单数据，如果是简单的数据：
	// processFormField
	if (item.isFormField()) {
	    String name = item.getFieldName();
	    String value = item.getString();
	    //...省略步骤
	}

	//如果是提交的文件：
	// processUploadedFile
	if (!item.isFormField()) {
	    String fieldName = item.getFieldName();
	    String fileName = item.getName();
	    String contentType = item.getContentType();
	    boolean isInMemory = item.isInMemory();
	    long sizeInBytes = item.getSize();
	    //...省略步骤
	}

	//对于这些item，我们通常要把它们写入文件，或转为一个流
	// Process a file upload
	if (writeToFile) {
	    File uploadedFile = new File(...);
	    item.write(uploadedFile);
	} else {
	    InputStream uploadedStream = item.getInputStream();
	    //...省略步骤
	    uploadedStream.close();
	}

	//或转为字节数组保存在内存中：
	// Process a file upload in memory
	byte[] data = item.get();
	//...省略步骤
	//如果这个文件真的很大，你可能会希望向用户报告到底传了多少到服务端，让用户了解上传的过程
	//Create a progress listener
	ProgressListener progressListener = new ProgressListener(){
	   public void update(long pBytesRead, long pContentLength, int pItems) {
	       System.out.println("We are currently reading item " + pItems);
	       if (pContentLength == -1) {
	           System.out.println("So far, " + pBytesRead + " bytes have been read.");
	       } else {
	           System.out.println("So far, " + pBytesRead + " of " + pContentLength
	                              + " bytes have been read.");
	       }
	   }
	};
	upload.setProgressListener(progressListener);</pre>
<p> </p>
<p><strong>11、HttpClien </strong>基于HttpCore实 现的一个HTTP/1.1兼容的HTTP客户端，它提供了一系列可重用的客户端身份验证、HTTP状态保持、HTTP连接管理module。</p>
<pre class="java" name="code">//GET方法
import java.io.IOException;
import org.apache.commons.httpclient.*;
import org.apache.commons.httpclient.methods.GetMethod;
import org.apache.commons.httpclient.params.HttpMethodParams;

public class GetSample{
	public static void main(String[] args) {
		// 构造HttpClient的实例
		HttpClient httpClient = new HttpClient();
		// 创建GET方法的实例
		GetMethod getMethod = new GetMethod("http://www.ibm.com");
		// 使用系统提供的默认的恢复策略
		getMethod.getParams().setParameter(HttpMethodParams.RETRY_HANDLER,
				new DefaultHttpMethodRetryHandler());
		try {
			// 执行getMethod
			int statusCode = httpClient.executeMethod(getMethod);
			if (statusCode != HttpStatus.SC_OK) {
				System.err.println("Method failed: "
						+ getMethod.getStatusLine());
			}
			// 读取内容
			byte[] responseBody = getMethod.getResponseBody();
			// 处理内容
			System.out.println(new String(responseBody));
		} catch (HttpException e) {
			// 发生致命的异常，可能是协议不对或者返回的内容有问题
			System.out.println("Please check your provided http address!");
			e.printStackTrace();
		} catch (IOException e) {
			// 发生网络异常
			e.printStackTrace();
		} finally {
			// 释放连接
			getMethod.releaseConnection();
		}
	}
}

//POST方法
import java.io.IOException;
import org.apache.commons.httpclient.*;
import org.apache.commons.httpclient.methods.PostMethod;
import org.apache.commons.httpclient.params.HttpMethodParams;

public class PostSample{
	public static void main(String[] args) {
		// 构造HttpClient的实例
		HttpClient httpClient = new HttpClient();
		// 创建POST方法的实例
		String url = "http://www.oracle.com/";
		PostMethod postMethod = new PostMethod(url);
		// 填入各个表单域的值
		NameValuePair[] data = { new NameValuePair("id", "youUserName"),
		new NameValuePair("passwd", "yourPwd") };
		// 将表单的值放入postMethod中
		postMethod.setRequestBody(data);
		// 执行postMethod
		int statusCode = httpClient.executeMethod(postMethod);
		// HttpClient对于要求接受后继服务的请求，象POST和PUT等不能自动处理转发
		// 301或者302
		if (statusCode == HttpStatus.SC_MOVED_PERMANENTLY || 
		statusCode == HttpStatus.SC_MOVED_TEMPORARILY) {
		    // 从头中取出转向的地址
		    Header locationHeader = postMethod.getResponseHeader("location");
		    String location = null;
		    if (locationHeader != null) {
		     location = locationHeader.getValue();
		     System.out.println("The page was redirected to:" + location);
		    } else {
		     System.err.println("Location field value is null.");
		    }
		    return;
		}
	}
}</pre>
<p> </p>
<p><strong>12、IO </strong>对java.io的扩展 操作文件非常方便。</p>
<p> </p>
<pre class="java" name="code">//1．读取Stream

//标准代码：
InputStream in = new URL( "http://jakarta.apache.org" ).openStream();
try {
       InputStreamReader inR = new InputStreamReader( in );
       BufferedReader buf = new BufferedReader( inR );
       String line;
       while ( ( line = buf.readLine() ) != null ) {
          System.out.println( line );
       }
  } finally {
    in.close();
  }

//使用IOUtils

InputStream in = new URL( "http://jakarta.apache.org" ).openStream();
try {
    System.out.println( IOUtils.toString( in ) );
} finally {
    IOUtils.closeQuietly(in);
}

//2．读取文件
File file = new File("/commons/io/project.properties");
List lines = FileUtils.readLines(file, "UTF-8");
//3．察看剩余空间
long freeSpace = FileSystemUtils.freeSpace("C:/");</pre>
<p> </p>
<p><strong>13、Lang </strong>主要是一些公共的工具集合，比如对字符、数组的操作等等。<strong><br></strong></p>
<p><img src="http://dl.iteye.com/upload/picture/pic/122650/62814d31-3fda-3171-8efd-bd2805e0634f.png" width="270" alt="" height="235"></p>
<pre class="java" name="code">	// 1 合并两个数组: org.apache.commons.lang. ArrayUtils
		// 有时我们需要将两个数组合并为一个数组，用ArrayUtils就非常方便，示例如下：
		private static void testArr() {
			String[] s1 = new String[] { "1", "2", "3" };
			String[] s2 = new String[] { "a", "b", "c" };
			String[] s = (String[]) ArrayUtils.addAll(s1, s2);
			for (int i = 0; i &lt; s.length; i++) {
				System.out.println(s[i]);
			}
			String str = ArrayUtils.toString(s);
			str = str.substring(1, str.length() - 1);
			System.out.println(str + "&gt;&gt;" + str.length());

		}
		//2 截取从from开始字符串
		StringUtils.substringAfter("SELECT * FROM PERSON ", "from");
		//3 判断该字符串是不是为数字(0~9)组成，如果是，返回true 但该方法不识别有小数点和 请注意
		StringUtils.isNumeric("454534"); //返回true
		//4.取得类名
        System.out.println(ClassUtils.getShortClassName(Test.class));
        //取得其包名
        System.out.println(ClassUtils.getPackageName(Test.class));
       
        //5.NumberUtils
        System.out.println(NumberUtils.stringToInt("6"));
        //6.五位的随机字母和数字
        System.out.println(RandomStringUtils.randomAlphanumeric(5));
        //7.StringEscapeUtils
        System.out.println(StringEscapeUtils.escapeHtml("&lt;html&gt;"));
        //输出结果为&amp;lt;html&amp;gt;
        System.out.println(StringEscapeUtils.escapeJava("String"));
       
        //8.StringUtils,判断是否是空格字符
        System.out.println(StringUtils.isBlank("   "));
        //将数组中的内容以,分隔
        System.out.println(StringUtils.join(test,","));
        //在右边加下字符,使之总长度为6
        System.out.println(StringUtils.rightPad("abc", 6, 'T'));
        //首字母大写
        System.out.println(StringUtils.capitalize("abc"));
        //Deletes all whitespaces from a String 删除所有空格
        System.out.println( StringUtils.deleteWhitespace("   ab  c  "));
        //判断是否包含这个字符
        System.out.println( StringUtils.contains("abc", "ba"));
        //表示左边两个字符
        System.out.println( StringUtils.left("abc", 2));
        System.out.println(NumberUtils.stringToInt("33"));</pre>
<p> </p>
<p><strong>14、Logging </strong>提供的是一个Java 的日志接口,同时兼顾轻量级和不依赖于具体的日志实现工具。<strong><br></strong></p>
<p> </p>
<pre class="java" name="code">import org.apache.commons.logging.Log;
import org.apache.commons.logging.LogFactory;

	public class CommonLogTest {
	 private static Log log = LogFactory.getLog(CommonLogTest.class);
	 //日志打印
	 public static void main(String[] args) {
		 log.error("ERROR");
		 log.debug("DEBUG");
		 log.warn("WARN");
		 log.info("INFO");
		 log.trace("TRACE");
	  System.out.println(log.getClass());
	 }

	}</pre>
<p> </p>
<p><strong><br>15、Validator </strong>通用验证系统<span>，该组件提供了客户端和服务器端的数据验证框架。 <br></span></p>
<p> 验证日期</p>
<pre class="java" name="code">// 获取日期验证
      DateValidator validator = DateValidator.getInstance();

      // 验证/转换日期
      Date fooDate = validator.validate(fooString, "dd/MM/yyyy");
      if (fooDate == null) {
          // 错误 不是日期
          return;
      }</pre>
<p>表达式验证</p>
<pre class="java" name="code">// 设置参数
      boolean caseSensitive = false;
      String regex1   = "^([A-Z]*)(?:\\-)([A-Z]*)*$"
      String regex2   = "^([A-Z]*)$";
      String[] regexs = new String[] {regex1, regex1};

      // 创建验证
      RegexValidator validator = new RegexValidator(regexs, caseSensitive);

      // 验证返回boolean
      boolean valid = validator.isValid("abc-def");

      // 验证返回字符串
      String result = validator.validate("abc-def");

      // 验证返回数组
      String[] groups = validator.match("abc-def");</pre>
<p> <span>配置文件中使用验证</span></p>
<pre class="xml" name="code">&lt;form-validation&gt;
   &lt;global&gt;
       &lt;validator name="required"
          classname="org.apache.commons.validator.TestValidator"
          method="validateRequired"
          methodParams="java.lang.Object, org.apache.commons.validator.Field"/&gt;
    &lt;/global&gt;
    &lt;formset&gt;
    &lt;/formset&gt;
&lt;/form-validation&gt;

添加姓名验证.

&lt;form-validation&gt;
   &lt;global&gt;
       &lt;validator name="required"
          classname="org.apache.commons.validator.TestValidator"
          method="validateRequired"
          methodParams="java.lang.Object, org.apache.commons.validator.Field"/&gt;
    &lt;/global&gt;
    &lt;formset&gt;
       &lt;form name="nameForm"&gt;
          &lt;field property="firstName" depends="required"&gt;
             &lt;arg0 key="nameForm.firstname.displayname"/&gt;
          &lt;/field&gt;
          &lt;field property="lastName" depends="required"&gt;
             &lt;arg0 key="nameForm.lastname.displayname"/&gt;
          &lt;/field&gt;
       &lt;/form&gt;
    &lt;/formset&gt;
&lt;/form-validation&gt; </pre>
<p> 验证类</p>

<pre class="java" name="code"> Excerpts from org.apache.commons.validator.RequiredNameTest
//加载验证配置文件
InputStream in = this.getClass().getResourceAsStream("validator-name-required.xml");

ValidatorResources resources = new ValidatorResources(in);
//这个是自己创建的bean 我这里省略了
Name name = new Name();

Validator validator = new Validator(resources, "nameForm");
//设置参数
validator.setParameter(Validator.BEAN_PARAM, name);


Map results = null;
//验证
results = validator.validate();

if (results.get("firstName") == null) {
    //验证成功
} else {
    //有错误     int errors = ((Integer)results.get("firstName")).intValue();
} </pre>
<p> </p>
  </div>

  


  