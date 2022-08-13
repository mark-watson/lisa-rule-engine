# Clone of David E. Young's Lisa Rate Network based rule system

I cloned this from Sourceforge with the intent on getting the examples easily configured to run and in the future do Rete Network experiments that I used to do with OPS5 in the 1980s.

David E. Young released Lisa under the LGPL v2 license.

# Example

```lisp
$ lispworks
* (load "install.lisp")
* (load "misc/mycin.lisp")
* (LISA-USER::CULTURE-1)
Identity: PSEUDOMONAS (0.760)
Identity: ENTEROBACTERIACEAE (0.800)
5
'''