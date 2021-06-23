# thewindinoursails
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

Requirements:
  - Docker
  - GRAPHDB SE license
  - Metaphactory license
  - 16GB RAM or more recommended
