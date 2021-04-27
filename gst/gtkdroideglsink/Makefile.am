noinst_LTLIBRARIES = libgstgtkdroideglsink.la
libgstgtkdroideglsink_la_CFLAGS = $(GST_CFLAGS) $(NGI_CFLAGS) $(EGL_CFLAGS) \
			       -I$(top_builddir)/gst-libs/ \
			       -I/usr/include/droidmedia/ \
			       -I/usr/include/gtk-3.0/

libgstgtkdroideglsink_la_LIBADD = $(GST_LIBS) $(NGI_LIBS) $(EGL_LIBS)

libgstgtkdroideglsink_la_SOURCES = gstgtkdroideglsink.c gtkgstbasewidget.c gstgtkbasesink.c gstgtkutils.c gtkgstglwidget.c
noinst_HEADERS = gstgtkdroideglsink.h gstgtkbasesink.h gtkgstglwidget.h gstgtkutils.h gtkgstbasewidget.h
