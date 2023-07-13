# haproxy-ocsp-elyograg

The get_ocsp_stapling script goes in /usr/local/sbin.  The ocsp_list.cfg file goes in /usr/local/etc.

A stats socket must be added to the global section of the haproxy config.  See haproxy_addition.cfg for details.

If you edit these files, you can change any of the filenames if that is required for your setup.
