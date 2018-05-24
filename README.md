# blast_pipeline
build blast database and do blast

# An example of blastp
* make blastp db<br>
makeblastdb -in target.fa -dbtype prot<br>
* do blastp<br>
blastp -query query.fa -db target.fa -num_threads 24 -max_target_seqs 1 -outfmt 6 > query.in.target.merged.outfmt6<br>
