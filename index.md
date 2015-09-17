---
layout: pagewithoutposts
title: Introduction
---
<p/>
<br>
INGENME is the acronym for INGENIAS Meta-Editor. It is a tool for producing self-contained visual editors for languages defined using an
XML file. It is a simpler alternative to Eclipse GMF since it requires minimal input to produce a common visual editor. You can use INGENME to test your visual language and then produce your own customized editor, or you can decide produced editors are good enough.
<br>
INGENME is maven based. Official dependencies are under the groupid *sf.net.ingenme* and developer *escalope*. To use INGENME, the quickest way is to download the template from github [https://github.com/escalope/template-ingenme](https://github.com/escalope/template-ingenme)

INGENME bases on generative programming techniques and a combination of concrete and abstract syntax to declare the language. These techniques are known to model driven developers but have no reuse of standard EMF/GMF frameworks. 

The distribution is completely maven based. This means:

- You can stick to stable versions of INGENME. Anyone.
- The products of an INGENME project is yet another Maven artifact. 
- If you are not using Maven in your development, you can still use other products from INGENME, like the self-contained editors
- The language development will stick to Maven lifecycle. This implies zero changes if you are used to Maven. 
- It is possible to produce sites documenting the developed language. This includes snapshots of the diagrams and whatever added text description. Text description is processed as if it was markdown text. Therefore, it is easy to produce formatted text with little effort.

The source code for INGENME is hosted in github at [https://github.com/Grasia/ingenme](https://github.com/Grasia/ingenme). You can download it and install it, thought it is not really necessary. This template works with stable versions hosted into maven central. 

<div style="float:center;margin:0 10px 10px 0" markdown="1">
![Logo INGENME](assets/img/logblackingenme.png)
</div>
