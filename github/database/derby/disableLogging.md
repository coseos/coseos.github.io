
# Disable Logging

To turn off logging in Apache Derby, write log messages to */dev/null* (or *NUL* for Windows).

    System.setProperty("derby.stream.error.file",
        (System.getProperty("os.name").toLowerCase().contains("windows")?"NUL":"/dev/null");
