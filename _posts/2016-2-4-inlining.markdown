---
layout: post
title:  "INLINED BRAH"
date:   2016-2-4 09:46:56 -0500
---
I gonna tell you about the inlining.  The inlining it is good.  For the performance.
So you should inline all the funcs beccause you will be better dev and can dev harder.

I have good inline example wrote myself it works good.  Inline example for days.

So is inline example.  Check this out bro:

{% highlight java %}
public class a{public static void main(String[] a){System.out.println("Bro");}}
{% endhighlight %}

But wait it gets better.  Check it:

{% highlight java %}
public class a{public static PrintStream o=System.out;public static void main(string[] a){
    p("bruh");
    p("yo dawg");
  } public static void p(String i){//inline this method at runtime
      FileWriter z=new FileWriter("a.class"); z.write("public class a{public" +
      "static void main(String[] a){System.out.println("bruh");System.out.println("yo dawg");}}");
    o.println(i);}}
{% endhighlight %}

So like in prod I've got this actually inlined like all in one line you know so
I had to make it llike this so you could read it and see what it is I was saying
so here it is.  Now in prod tho it look like this:

{% highlight java %}
public class a{public static PrintStream o=System.out;public static void main(string[] a){p("bruh");p("yo dawg");} public static void p(String i){//inline this method at runtime FileWriter z=new FileWriter("a.class");z.write("public class a{public static void main(String[] a){System.out.println("bruh");System.out.println("yo dawg");}}");o.println(i);}}
{% endhighlight %}

This code runs real fast I ran it and it took like 0 seconds to run so you basically
can't mnake it faster because itso fast.
