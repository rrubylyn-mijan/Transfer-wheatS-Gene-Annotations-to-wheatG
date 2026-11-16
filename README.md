# Transfer-wheatS-Gene-Annotations-to-wheatG
This command uses Liftoff to transfer gene annotations from the wheatS genome assembly onto the wheatG genome assembly.

```bash
Required inputs:
wheatS.gff3  (source gene annotation)
wheatS.fa  (source genome assembly)
wheatG.fa (target genome assembly)
```

```bash
# Run Liftoff
With Liftoff installed and available in your environment, run:

liftoff \
  -g wheatS.gff3 \
  -o wheatS_to_wheatG_liftoff.gff3 \
  -p 48 \
  wheatG.fa \
  wheatS.fa
```
