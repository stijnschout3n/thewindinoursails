# thewindinoursails

Changelog:
- 06/07/2021: found a small mistake in the BGB DAS mapping. dfhc:P9 should be dfhc:P12 in mapping goods to monetary amounts. Is updated in the Gdrive
- 30-08-2021: Lodewijk discovered that the Docker container does not contain the templates. todo: upload version to the shared drive that contains the templates as well. Planned on Thursday. 

Information and downloads 

Link to the shared directory:
https://drive.google.com/drive/folders/1yB5sbaixgBJoUYAeVfv386dl46RiSKuM?usp=sharing

Directory information:
  - Data Archive: ignore
  - Version1: results of first design iteration
  - Version2: results of the second(and final) iteration:
    - BGB: BGB mapping folder:
      - DAS: BGB DAS variant mapping folder:
        - openrefine project: can be imported in the openrefine environment;
        - mapping.json: can be imported in the rdf mapping of openrefine;
        - results triples: can be imported in any graph database;
        - input: input csv of the projects.
       - NODAS: BGB NODAS variant mapping folder.
     - DAS: DAS voyages mapping folder.
     - PLACES: VOC Places mapping folder.
     - VOCOP: VOC Opvarenden mapping folder.
  - docker container: docker container, can be initialized with the command "docker-compose -d" with PowerShell. First navigate to the "my-deployment" folder.

Thesis (to be uploaded), including appendices, is included: https://github.com/stijnschout3n/thewindinoursails/blob/main/Thesis_Stijn_Schouten_V1_with_bib.pdf

The ontology, in .ttl format, is included: https://github.com/stijnschout3n/thewindinoursails/blob/main/maritimehistorycontinued_V1.rdf


Requirements:
  - Docker
  - GRAPHDB SE license
  - Metaphactory license
  - 16GB RAM or more recommended
