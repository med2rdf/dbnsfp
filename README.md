# dbNSFP


Download data from 
https://sites.google.com/site/jpopgen/dbNSFP

run docker command

# docker build -t dbnsfp .
# docker run -v /hoge:/data dbnsfp ruby /work/mkRDFdbNSFP.rb /work/academic.conf /data/dbNSFPxxxa.chrx

It outputs /hoge/dbNSFPxxxa.chrx.ttl.
You can replace academic.conf for customizing the rdf.

スキーマ図は以下サイトにて作成
https://www.kanzaki.com/works/2009/pub/graph-draw




