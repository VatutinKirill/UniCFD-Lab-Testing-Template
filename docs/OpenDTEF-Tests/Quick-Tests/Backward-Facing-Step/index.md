![UniCFD_logo](https://raw.githubusercontent.com/VatutinKirill/UniCFD-Lab-Testing/master/docs/small_final_compact.png)
# Modeling results
![UniCFD_logo](https://raw.githubusercontent.com/VatutinKirill/UniCFD-Lab-Testing/master/docs/small_final_compact.png)

# About Backward-Facing Step case

Backward-Facing Step (BFS) is widely known for its application in the studies on turbulence in flows. The flow separation is caused due to the sudden changes in the geometry. This creates a zone of re-circulation and a point of flow reattachment. The present numerical study focuses on the re-attachment lengths of one such Backward Facing Step problem. The flow velocity depends on the Reynold number and this numerical study has been carried out for different Reynold numbers. Steady State standard k-ε turbulence model was used for conducting the numerical simulations in the OpenDTEF open-source software package. 

[Case on GitHub](./case).

### Last Backward-Facing Step Tests (№ N)

| № | test № _ _ _ _ _             | status     | time                     |    duration   | log file |
|:--|:-----------------------------|:-----------|:-------------------------|:--------------|:---------|
|  1| blockMesh                    | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
|  2| snappyHexMesh                | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
|  3| checkMesh                    | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
|  4| renumberMesh                 | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
|  5| funkySetFields               | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
|  6| simpleFOAM                   | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
|  7| decomposePar                 | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
|  8| simpleFOAM -parallel         | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
|  9| reconstructPar               | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
| 10| postProcess -func sampleDict | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
| 11| foamToVTK                    | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
| 12| checkValues.sh               | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |

...

### (N-2)

...

### Backward-Facing Step Tests (№ 1)

| № | test № _ _ _ _ _             | status     | time                     |    duration   | log file |
|:--|:-----------------------------|:-----------|:-------------------------|:--------------|:---------|
|  1| blockMesh                    | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
|  2| snappyHexMesh                | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
|  3| checkMesh                    | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
|  4| renumberMesh                 | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
|  5| funkySetFields               | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
|  6| simpleFOAM                   | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
|  7| decomposePar                 | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
|  8| simpleFOAM -parallel         | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
|  9| reconstructPar               | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
| 10| postProcess -func sampleDict | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
| 11| foamToVTK                    | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
| 12| checkValues.sh               | (OK/FAILD) | mon ** , 20** ** : ** ** | *** : ** : ** |    ???   |
