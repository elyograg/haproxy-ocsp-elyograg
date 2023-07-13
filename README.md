# haproxy-ocsp-elyograg

The get_ocsp_stapling script goes in /usr/local/sbin.  The ocsp_list.cfg file goes in /usr/local/etc.

A stats socket must be added to the global section of the haproxy config.  See haproxy_addition.cfg for details.

If you edit these files, you can change any of the filenames if that is required for your setup.

The config file has two filenames on each line.  The first is the PEM filename which has the leaf certificate as the first item.  The second is the PEM filename which has the issuing certificate as the first item.

