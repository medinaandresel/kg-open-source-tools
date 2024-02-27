# kg-tools

## Overview ontology editors


<table>
  <thead>
    <tr>
      <th></th>
      <th style="text-align: center;" colspan="3">general description</th>
      <th style="text-align: center;" colspan="3">multi-user support</th>
    </tr>
    <tr>
      <th>editor</th>
      <th>short description</th>
      <th>developers & maintainers</th>
      <th>license</th>
      <th>user roles</th>
      <th>project administration</th>
      <th>content validation (consistency)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/obdasystems/eddy">Eddy</a></td>
      <td>Ontology creation and management.</td>
      <td>DASI-lab group, University of Rome</td>
      <td>GPLV3</td>
      <td>-</td>
      <td>system log</td>
      <td>Graphol, HermiT</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Semantic-Society/Neologism">Neologism</a></td>
      <td>Neologism~2.0 is a tool  for quick vocabulary creation.</td>
      <td>Semantic Society (6 persons)</td>
      <td>MIT</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td><a href="https://github.com/protegeproject/protege">Protégé</a></td>
      <td>Protégé can be customized for building both simple and complex ontology-based applications. Developers can integrate the output of Protégé with rule systems or other problem solvers to create a wide range of intelligent systems.</td>
      <td>Standford Team & Protege Community</td>
      <td>Stanford/ BSD 2-clause</td>
      <td>-</td>
      <td>-</td>
      <td>HermiT, Pellet, Ontop, FaCT++, ELK</td>
    </tr>
    <tr>
      <td><a href="https://github.com/protegeproject/webprotege">WebProtégé</a></td>
      <td>It is a free and open-source environment for collaborative ontology development. It operates as a web application. End users access it through their web browsers. They do not need to download or install any software.</td>
      <td>Standford Team & Protege Community</td>
      <td>Stanford/ BSD 2-clause</td>
      <td>Allows for the setting of user permissions (view, comment, edit, and manage)</td>
      <td>history tracking, users can add comments, access control</td>
      <td>-</td>
    </tr>
    <tr>
      <td><a href="https://vocbench.uniroma2.it">VocBench</a></td>
      <td>It is a web-based, multilingual, collaborative development platform for managing OWL ontologies, SKOS(/XL) thesauri, Ontolex-lemon lexicons and generic RDF datasets.</td>
      <td>ART Group,  University of Tor Vergata</td>
      <td>UniRome/ BSD 3-clause</td>
      <td>With the following permissions: administrator and user. Different roles can be assigned to users.</td>
      <td>validation, history tracking & versioning, access control</td>
      <td>features a set of Integrity Constraint Validation (ICV) checks</td>
    </tr>
    <tr>
      <td><a href="https://github.com/vivo-project/Vitro">Vitro</a></td>
      <td>It is a general-purpose web-based ontology and instance editor with customizable public browsing. Vitro is primarily used as a key software component in the open-source VIVO project. VIVO is member-supported, open source software and an ontology for representing scholarship.</td>
      <td>VIVO Community</td>
      <td>Cornell/ BSD 3-clause</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td><a href="https://github.com/felixocker/ontor">ontor</a></td>
      <td>Ontology editor built on Owlready2, which supports the following features: creating new, loading and modifying existing, saving, reasoning and visualizing ontologies.</td>
      <td>3 contributors</td>
      <td>GPLV3</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
  </tbody>
</table>






<table>
  <thead>
    <tr>
      <th></th>
      <th style="text-align: center;" colspan="4">software architecture</th>
      <th style="text-align: center;" colspan="2">interoperability & reasoning</th>
      <th style="text-align: center;" colspan="3">software maintenance</th>
    </tr>
    <tr>
      <th>editor</th>
      <th>deployment</th>
      <th>extensions</th>
      <th>storage</th>
      <th>API</th>
      <th>supported formats</th>
      <th>reasoning</th>
      <th>popularity / hosted</th>
      <th>last update</th>
      <th>documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/obdasystems/eddy">Eddy</a></td>
      <td>desktop (windows, linux, macOS)</td>
      <td>plugins</td>
      <td>-</td>
      <td>-</td>
      <td>OWL 2 QL, RL</td>
      <td>-</td>
      <td>49 stars, 6 forks / github</td>
      <td>10/2023</td>
      <td>detailed</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Semantic-Society/Neologism">Neologism</a></td>
      <td>web</td>
      <td>-</td>
      <td>MongoDB</td>
      <td>REST API</td>
      <td>RDF</td>
      <td>-</td>
      <td>6 stars, 3 forks / github</td>
      <td>11/2023</td>
      <td>short</td>
    </tr>
    <tr>
      <td><a href="https://github.com/protegeproject/protege">Protégé</a></td>
      <td>desktop (windows, linux, macOS)</td>
      <td>large number of plugins available</td>
      <td>MySQL</td>
      <td>-</td>
      <td>OWL 2 and the profiles: OWL 2 QL, RL, EL, RDF, RDFS</td>
      <td>HermiT, Pellet, Ontop, FaCT++, ELK</td>
      <td>892 stars, 229 forks / github</td>
      <td>11/2023</td>
      <td>detailed</td>
   </tr>
    <tr>
      <td><a href="https://github.com/protegeproject/webprotege">WebProtégé</a></td>
      <td>web</td>
      <td>-</td>
      <td>MongoDB</td>
      <td>-</td>
      <td>OWL 2 and the profiles: OWL 2 QL, RL,  EL, RDF, RDFS</td>
      <td>-</td>
      <td>584 stars, 246 forks / github</td>
      <td>10/2023</td>
      <td>detailed</td>
   </tr>
    <tr>
      <td><a href="https://vocbench.uniroma2.it">VocBench</a></td>
      <td>web</td>
      <td>-</td>
      <td>triple store</td>
      <td>Web API</td>
      <td>OWL2, OWL, RDFS, SKOS, OntoLex, EDOAL</td>
      <td>depends on triple store</td>
      <td>218 downloads since 09/2023 / bitbucket</td>
      <td>11/2023</td>
      <td>detailed</td>
    </tr>
    <tr>
      <td><a href="https://github.com/vivo-project/Vitro">Vitro</a></td>
      <td>web</td>
      <td>-</td>
      <td>MySQL</td>
      <td>-</td>
      <td>RDF/XML, N-Triples, Turtle, N3, RDFa, JSON-LD, TriG, OWL</td>
      <td>-</td>
      <td>86 stars, 86 forks / github</td>
      <td>11/2023</td>
      <td>minimal</td>
    </tr>
    <tr>
      <td><a href="https://github.com/felixocker/ontor">ontor</a></td>
      <td>desktop (python-based)</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>OWL2</td>
      <td>-</td>
      <td>26 stars, 4 forks / github</td>
      <td>03/2023</td>
      <td>short</td>
    </tr>
  </tbody>
</table>




## Overview of usable and/or maintained reasoners



<table>
  <thead>
    <tr>
      <th>Reasoner</th>
      <th>Description</th>
      <th>Language</th>
      <th>Implementation</th>
      <th>Scalability</th>
      <th>In-memory</th>
      <th>Maintained</th>
      <th>Usable</th>
      <th>Licence</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ERGS <a href="#footnote_ERGS">[1]</td>
      <td>"OWL reasoner and an RDF triple store built on top of a Property Graph architecture. ERGS uses Janus Graph as the underlying graph store which can be replaced by any Apache TinkerPop compliant graph store"</td>
      <td>RDFS, limited OWL & Java</td>
      <td>Java</td>
      <td style="text-align: center;">&#x2713;</td>
      <td style="text-align: center;">&#x2717;</td>
      <td style="text-align: center;">&#x2713;</td>
      <td style="text-align: center;">&#x2713;</td>
      <td>Apache 2.0</td>
    </tr>
    <tr>
     <td>Arachne <a href="#footnote_Arachne">[2]</td>
      <td>"an RDF rule engine with support for efficient reasoning with large OWL RL terminologies[...]Its architecture is well suited to applications of large ontologies to instance-based datasets, supporting new approaches to utilizing the rich semantics represented within the Gene Ontology and related scientific ontologies"</td>
      <td>OWL RL</td>
      <td>Scala</td>
      <td style="text-align: center;">&#x2713;</td>
      <td style="text-align: center;">&#x2713;</td>
      <td style="text-align: center;">&#x2713;</td>
      <td style="text-align: center;">&#x2713;</td>
      <td>BSD</td>
    </tr>
    <tr>
      <td>CEL <a href="#footnote_CEL">[3]</td>
      <td>"a lightweight Description Logic reasoner for large-scale biomedical ontologies. The CEL Plug-ing uses the OWL API and lets CEL be used as a plug-in for Protege "</td>
      <td>OWL 2 EL</td>
      <td>LIPS, Java</td>
      <td style="text-align: center;">&#x2717;</td>
      <td style="text-align: center;">&#x2713;</td>
      <td style="text-align: center;">&#x2713;</td>
      <td style="text-align: center;">&#x2713;</td>
      <td>Apache 2.0</td>
    </tr>
    <tr>
      <td>Konclude <a href="#footnote_Konclude">[4]</td>
      <td>"A parallel, tableau-based, high-performance reasoner for the Description Logic SROIQV(D)/the Web Ontology Language (OWL) 2 DL"</td>
      <td>OWL 2 DL</td>
      <td>C++</td>
      <td style="text-align: center;">&#x2713;</td>
      <td style="text-align: center;">&#x2713;</td>
      <td style="text-align: center;">&#x2713;</td>
      <td style="text-align: center;">&#x2713;</td>
      <td>LGPLv3</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Galigator/openllet">Openllet</a></td>
      <td>"An Open Source OWL DL reasoner for Java. Openllet provides functionality to check consistency of ontologies, compute the classification hierarchy, explain inferences, and answer SPARQL queries."</td>
      <td>OWL 2</td>
      <td>Java</td>
      <td style="text-align: center;">&#x2717;</td>
      <td style="text-align: center;">&#x2713;</td>
      <td style="text-align: center;">&#x2713;</td>
      <td style="text-align: center;">&#x2713;</td>
      <td>AGPL or commercial license</td>
    </tr>
    <tr>
      <td>NORA <a href="#footnote_NORA">[5]</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>

     \cite{DBLP:journals/spe/BenitezHidalgoNG23} & "Pellet, a well-known OWL 2 DL reasoner, is used to classify on the TBox. By combining these tools, we obtain several taxonomies, such as the class/subclass and property/subproperty hierarchies, but no newly derived knowledge is inferred from the ABox. Subsequently, a database schema is created to materialise all this information.17 As a result, the reasoned TBox is stored in Cassandra together with the explicit instances" & OWL 2 & Java & \cmark & \xmark & \cmark & \cmark & MIT \\ \hline \\


    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
   <tfoot>
      <tr>
        <td colspan="9" id="footnote_ERGS"> [1] Neelam, S., Sharma, U., Bhatia, S., Karanam, H., Likhyani, A., Abdelaziz, I., Fokoue, A., Subramaniam, L.V.: Expressive reasoning graph store: A unified framework for managing RDF and property graph databases. CoRR abs/2209.05828 (2022).</td>
      </tr>
      <tr>
        <td colspan="9" id="footnote_Arachne"> [2] Neelam, S., Sharma, U., Bhatia, S., Karanam, H., Likhyani, A., Abdelaziz, I., Fokoue, A., Subramaniam, L.V.: Expressive reasoning graph store: A unified framework for managing RDF and property graph databases. CoRR abs/2209.05828 (2022).</td>
      </tr>

    </tfoot>
</table>


