AC_INIT(myconfig, 0.1)

AC_PROG_CXX()
AC_LANG(C++)

CFLAGS="-DDEBUG -g"

AC_CHECK_HEADERS([pcap.h gtest/gtest.h])
AC_CHECK_LIB(pcap, pcap_loop, [], [AC_MSG_ERROR([pcap library is needed!])])
#AC_CHECK_LIB([gtest_main], [main], [], [AC_MSG_ERROR([gtest library is needed!])])
AC_SUBST(CFLAGS)
AC_OUTPUT(Makefile)