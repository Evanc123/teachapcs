# Converting Wrapped primitives to primitives
While <word data-key="object">objects</word> can be useful, sometimes we prefer to work with <word data-key="primitive">primitives</word>. Here's how we go from a <word data-key="wrapper">Wrapper class</word> to a primitive:

    Integer i = new Integer(4);
    int j = i.intValue();
    // j now has the value 4

    Double d = new Double(5.2);
    double e = d.doubleValue();
    // e now has the value 5.2

    Boolean b = new Boolean(true);
    boolean c = b.booleanValue();
    // c now has the value true

[Java 5.0+](http://en.wikipedia.org/wiki/Java_version_history#J2SE_5.0_.28September_30.2C_2004.29) automatically converts between <word data-key="primitive">primitives</word> and wrapped <word data-key="object">objects</word> by <word data-key="autoboxing">autoboxing</word>.