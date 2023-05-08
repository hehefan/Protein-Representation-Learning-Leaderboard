# Awesome Protein Representation Learning
If you find any related paper, please kindly let us know. We will keep updating the page. Thanks for your valuable contribution.

## Supervised Method

<table>
    <tr>
        <td rowspan="2" align="center">NO.</td>
        <td rowspan="2" align="center">Method</td>
        <td colspan="2" align="center">EC</td>
        <td colspan="2" align="center">GO-BP</td>
        <td colspan="2" align="center">GO-MF</td>
        <td colspan="2" align="center">GO-CC</td>
        <td>Fold-Fold</td>
        <td>Fold-Superfamily</td>
        <td>Fold-Family</td>
        <td>Reaction</td>
    </tr>
    <tr>
        <td align="center"> Fmax</td>
        <td align="center">AUPR</td>
        <td align="center">Fmax</td>
        <td align="center">AUPR</td>
        <td align="center">Fmax</td>
        <td align="center">AUPR</td>
        <td align="center">Fmax</td>
        <td align="center">AUPR</td>
        <td colspan="4" align="center">Accuracy</td>
    </tr>
    <tr align="center">
        <td>1</td>
        <td><a href="https://github.com/googleinterns/protein-embedding-retrieval/blob/master/cnn_protein_landscapes.ipynb">CNN</a></td>
        <td>0.545</td>
        <td>0.526</td>
        <td>0.244</td>
        <td>0.159</td>
        <td>0.354</td>
        <td>0.351</td>
        <td>0.287</td>
        <td>0.204</td>
        <td>0.113</td>
        <td>0.134</td>
        <td>0.534</td>
        <td>0.517</td>
    </tr>
    <tr align="center">
        <td>2</td>
        <td> <a href="https://github.com/songlab-cal/tape">ResNet</a></td>
        <td>0.605</td>
        <td>0.590</td>
        <td>0.280</td>
        <td>0.205</td>
        <td>0.405</td>
        <td>0.434</td>
        <td>0.304</td>
        <td>0.214</td>
        <td>0.101</td>
        <td>0.072</td>
        <td>0.235</td>
        <td>0.241</td>
    </tr>
    <tr align="center">
        <td>3</td>
        <td><a href="https://github.com/songlab-cal/tape">LSTM</a></td>
        <td>0.425</td>
        <td>0.414</td>
        <td>0.225</td>
        <td>0.156</td>
        <td>0.321</td>
        <td>0.334</td>
        <td>0.283</td>
        <td>0.192</td>
        <td>0.064</td>
        <td>0.043</td>
        <td>0.181</td>
        <td>0.110</td>
    </tr>
    <tr align="center">
        <td>4</td>
        <td><a href="https://github.com/songlab-cal/tape">Transformer</a></td>
        <td>0.238</td>
        <td>0.218</td>
        <td>0.264</td>
        <td>0.156</td>
        <td>0.211</td>
        <td>0.177</td>
        <td>0.405</td>
        <td>0.210</td>
        <td>0.092</td>
        <td>0.088</td>
        <td>0.404</td>
        <td>0.266</td>
    </tr>
    <tr align="center">
        <td>5</td>
        <td><a href="https://github.com/DeepGraphLearning/torchdrug/blob/master/torchdrug/models/gcn.py">GCN</a></td>
        <td>0.320</td>
        <td>0.319</td>
        <td>0.252</td>
        <td>0.136</td>
        <td>0.195</td>
        <td>0.147</td>
        <td>0.329</td>
        <td>0.175</td>
        <td>0.168</td>
        <td>0.213</td>
        <td>0.828</td>
        <td>0.673</td>
    </tr>
    <tr align="center">
        <td>6</td>
        <td><a href="https://github.com/DeepGraphLearning/torchdrug/blob/master/torchdrug/models/gat.py">GAT</a></td>
        <td>0.368</td>
        <td>0.320</td>
        <td>0.284</td>
        <td>0.171</td>
        <td>0.317</td>
        <td>0.319</td>
        <td>0.385</td>
        <td>0.249</td>
        <td>0.124</td>
        <td>0.165</td>
        <td>0.727</td>
        <td>0.556</td>
    </tr>
    <tr align="center">
        <td>7</td>
        <td> <a href="https://github.com/COMP6248-Reproducability-Challenge/Geometric-Vector-Perceptron/tree/master">GVP</a></td>
        <td>0.489</td>
        <td>0.482</td>
        <td>0.326</td>
        <td>0.224</td>
        <td>0.426</td>
        <td>0.458</td>
        <td>0.420</td>
        <td>0.279</td>
        <td>0.160</td>
        <td>0.225</td>
        <td>0.838</td>
        <td>0.655</td>
    </tr>
    <tr align="center">
        <td>8</td>
        <td><a href="https://github.com/lamoureux-lab/3DCNN_MQA/tree/pytorch1.0">3DCNN_MQA</a></td>
        <td>0.077</td>
        <td>0.029</td>
        <td>0.240</td>
        <td>0.132</td>
        <td>0.147</td>
        <td>0.075</td>
        <td>0.305</td>
        <td>0.144</td>
        <td>0.316</td>
        <td>0.454</td>
        <td>0.925</td>
        <td>0.722</td>
    </tr>
    <tr align="center">
        <td>9</td>
        <td><a href="https://github.com/baldassarreFe/graphqa">GraphQA</a></td>
        <td>0.509</td>
        <td>0.543</td>
        <td>0.308</td>
        <td>0.199</td>
        <td>0.329</td>
        <td>0.347</td>
        <td>0.413</td>
        <td>0.256</td>
        <td>0.237</td>
        <td>0.325</td>
        <td>0.844</td>
        <td>0.608</td>
    </tr>
        <tr align="center">
        <td>10</td>
        <td><a href="https://github.com/phermosilla/IEConv_proteins">IEConv-I</a></td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>0.450</td>
        <td>0.697</td>
        <td>0.989</td>
        <td>0.872</td>
    </tr>
    <tr align="center">
        <td>11</td>
        <td><a href="https://arxiv.org/abs/2205.15675">IEConv-II</a></td>
        <td>0.735</td>
        <td>0.775</td>
        <td>0.374</td>
        <td>0.273</td>
        <td>0.544</td>
        <td>0.572</td>
        <td>0.444</td>
        <td>0.316</td>
        <td>0.476</td>
        <td>0.702</td>
        <td>0.992</td>
        <td>0.872</td>
    </tr>
    <tr align="center">
        <td>12</td>
        <td><a href="https://github.com/DeepGraphLearning/GearNet">GearNet</a></td>
        <td>0.730</td>
        <td>0.751</td>
        <td>0.356</td>
        <td>0.211</td>
        <td>0.503</td>
        <td>0.490</td>
        <td>0.414</td>
        <td>0.276</td>
        <td>0.284</td>
        <td>0.426</td>
        <td>0.953</td>
        <td>0.794</td>
    </tr>
    <tr align="center">
        <td>13</td>
        <td><a href="https://github.com/DeepGraphLearning/GearNet">GearNet-IEConv</a></td>
        <td>0.800</td>
        <td>0.835</td>
        <td>0.381</td>
        <td>0.231</td>
        <td>0.563</td>
        <td>0.547</td>
        <td>0.422</td>
        <td>0.259</td>
        <td>0.423</td>
        <td>0.641</td>
        <td>0.991</td>
        <td>0.837</td>
    </tr>
    <tr align="center">
        <td>14</td>
        <td><a href="https://github.com/DeepGraphLearning/GearNet">GearNet-Edge</a></td>
        <td>0.810</td>
        <td>0.872</td>
        <td>0.403</td>
        <td>0.251</td>
        <td>0.580</td>
        <td>0.570</td>
        <td>0.450</td>
        <td>0.303</td>
        <td>0.440</td>
        <td>0.667</td>
        <td>0.991</td>
        <td>0.866</td>
    </tr>
    <tr align="center">
        <td>15</td>
        <td><a href="https://github.com/DeepGraphLearning/GearNet">GearNet-Edge-IEConv</a></td>
        <td>0.810</td>
        <td>0.843</td>
        <td>0.400</td>
        <td>0.244</td>
        <td>0.581</td>
        <td>0.561</td>
        <td>0.430</td>
        <td>0.284</td>
        <td>0.483</td>
        <td>0.703</td>
        <td>0.995</td>
        <td>0.853</td>
    </tr>
    <tr align="center">
        <td>16</td>
        <td><a href="https://arxiv.org/abs/2207.12600">ProNet-Amino-Acid</a></td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td>0.515</td>
        <td>0.699</td>
        <td>0.990</td>
        <td>0.860</td>
    </tr>
    <tr align="center">
        <td>17</td>
        <td><a href="https://arxiv.org/abs/2207.12600">ProNet-Backbone</a></td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td>0.527</td>
        <td>0.703</td>
        <td>0.993</td>
        <td>0.864</td>
    </tr>
    <tr align="center">
        <td>18</td>
        <td><a href="https://arxiv.org/abs/2207.12600">ProNet-All-Atom</a></td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td> - </td>
        <td>0.521</td>
        <td>0.690</td>
        <td>0.990</td>
        <td>0.856</td>
    </tr>
    <tr align="center">
        <td>19</td>
        <td><a href="https://github.com/hehefan/Continuous-Discrete-Convolution">CDConv</a></td>
        <td>0.820</td>
        <td> - </td>
        <td>0.453</td>
        <td> - </td>
        <td>0.654</td>
        <td> - </td>
        <td>0.479</td>
        <td> - </td>
        <td>0.567</td>
        <td>0.777</td>
        <td>0.996</td>
        <td>0.885</td>
    </tr>
</table>



## Pretrained Method
<table>
    <tr>
        <td rowspan="2" align="center">NO.</td>
        <td rowspan="2" align="center">Method</td>
        <td rowspan="2" align="center">Pre-training Dataset</td>
        <td colspan="2" align="center">EC</td>
        <td colspan="2" align="center">GO-BP</td>
        <td colspan="2" align="center">GO-MF</td>
        <td colspan="2" align="center">GO-CC</td>
        <td>Fold-Fold</td>
        <td>Fold-Superfamily</td>
        <td>Fold-Family</td>
        <td>Reaction</td>
    </tr>
    <tr>
        <td align="center">Fmax</td>
        <td align="center">AUPR</td>
        <td align="center">Fmax</td>
        <td align="center">AUPR</td>
        <td align="center">Fmax</td>
        <td align="center">AUPR</td>
        <td align="center">Fmax</td>
        <td align="center">AUPR</td>
        <td colspan="4" align="center">Accuracy</td>
    </tr>
    <tr align="center">
        <td>1</td>
        <td><a href="https://github.com/flatironinstitute/DeepFRI">DeepFRI</a></td>
        <td>Pfam (10 M)</td>
        <td>0.631</td>
        <td>0.547</td>
        <td>0.399</td>
        <td>0.282</td>
        <td>0.465</td>
        <td>0.462</td>
        <td>0.460</td>
        <td>0.363</td>
        <td>0.153</td>
        <td>0.206</td>
        <td>0.732</td>
        <td>0.633</td>
    </tr>
    <tr align="center">
        <td>2</td>
        <td><a href="https://github.com/facebookresearch/esm">ESM-1b</a></td>
        <td>Unifef 50 (24 M)</td>
        <td>0.864</td>
        <td>0.889</td>
        <td>0.470</td>
        <td>0.343</td>
        <td>0.657</td>
        <td>0.639</td>
        <td>0.488</td>
        <td>0.384</td>
        <td>0.268</td>
        <td>0.601</td>
        <td>0.978</td>
        <td>0.831</td>
    </tr>
    <tr align="center">
        <td>3</td>
        <td><a href="https://github.com/agemagician/ProtTrans">ProtBert-BFD</a></td>
        <td>BFD (2.1 B)</td>
        <td>0.838</td>
        <td>0.859</td>
        <td>0.279</td>
        <td>0.188</td>
        <td>0.456</td>
        <td>0.464</td>
        <td>0.408</td>
        <td>0.234</td>
        <td>0.266</td>
        <td>0.558</td>
        <td>0.976</td>
        <td>0.722</td>
    </tr>
    <tr align="center">
        <td>4</td>
        <td><a href="https://github.com/aws-samples/lm-gvp">LM-GVP</a></td>
        <td>Unifef100 (216 M)</td>
        <td>0.664</td>
        <td>0.710</td>
        <td>0.417</td>
        <td>0.302</td>
        <td>0.545</td>
        <td>0.580</td>
        <td>0.527</td>
        <td>0.423</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr align="center">
        <td>5</td>
        <td> <a href="https://arxiv.org/abs/2205.15675">IEConv-II</a></td>
        <td>PDB (476 K)</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>0.503</td>
        <td>0.806</td>
        <td>0.997</td>
        <td>0.876</td>
    </tr>
    <tr align="center">
        <td>6</td>
        <td><a href="https://github.com/tbepler/prose">MT-LSTM</a></td>
        <td>Unifef90 (76 M)</td>
        <td>0.817</td>
        <td>0.851</td>
        <td>0.442</td>
        <td>0.324</td>
        <td>0.591</td>
        <td>0.608</td>
        <td>0.492</td>
        <td>0.381</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr align="center">
        <td>7</td>
        <td><a href="https://github.com/DeepGraphLearning/GearNet">GearNet-Edge (Multiview Contrast)</a></td>
        <td>AlphaFoldDB (805 K)</td>
        <td>0.874</td>
        <td>0.982</td>
        <td>0.490</td>
        <td>0.292</td>
        <td>0.654</td>
        <td>0.596</td>
        <td>0.488</td>
        <td>0.336</td>
        <td>0.541</td>
        <td>0.805</td>
        <td>0.999</td>
        <td>0.875</td>
    </tr>
    <tr align="center">
        <td>8</td>
        <td><a href="https://github.com/DeepGraphLearning/GearNet">GearNet-Edge (Residue Type Prediction)</a></td>
        <td>AlphaFoldDB (805 K)</td>
        <td>0.843</td>
        <td>0.870</td>
        <td>0.430</td>
        <td>0.267</td>
        <td>0.604</td>
        <td>0.583</td>
        <td>0.465</td>
        <td>0.311</td>
        <td>0.488</td>
        <td>0.710</td>
        <td>0.994</td>
        <td>0.866</td>
    </tr>
    <tr align="center">
        <td>9</td>
        <td><a href="https://github.com/DeepGraphLearning/GearNet">GearNet-Edge (Distance Prediction)</a></td>
        <td>AlphaFoldDB (805 K)</td>
        <td>0.839</td>
        <td>0.863</td>
        <td>0.448</td>
        <td>0.274</td>
        <td>0.616</td>
        <td>0.586</td>
        <td>0.464</td>
        <td>0.327</td>
        <td>0.509</td>
        <td>0.735</td>
        <td>0.994</td>
        <td>0.875</td>
    </tr>
    <tr align="center">
        <td>10</td>
        <td><a href="https://github.com/DeepGraphLearning/GearNet">GearNet-Edge (Angle Prediction)</a></td>
        <td>AlphaFoldDB (805 K)</td>
        <td>0.853</td>
        <td>0.880</td>
        <td>0.458</td>
        <td>0.291</td>
        <td>0.625</td>
        <td>0.603</td>
        <td>0.473</td>
        <td>0.331</td>
        <td>0.565</td>
        <td>0.763</td>
        <td>0.996</td>
        <td>0.868</td>
    </tr>
    <tr align="center">
        <td>11</td>
        <td><a href="https://github.com/DeepGraphLearning/GearNet">GearNet-Edge (Dihedral Prediction)</a></td>
        <td>AlphaFoldDB (805 K)</td>
        <td>0.859</td>
        <td>0.881</td>
        <td>0.458</td>
        <td>0.304</td>
        <td>0.626</td>
        <td>0.603</td>
        <td>0.465</td>
        <td>0.338</td>
        <td>0.518</td>
        <td>0.778</td>
        <td>0.996</td>
        <td>0.870</td>
    </tr>
    <tr align="center">
        <td>12</td>
        <td><a href="https://openreview.net/forum?id=XGagtiJ8XC">PromptProtein</a></td>
        <td>UniRef50 + PDB + STRING (89 M) </td>
        <td>0.888</td>
        <td>0.915</td>
        <td>0.495</td>
        <td>0.363</td>
        <td>0.677</td>
        <td>0.665</td>
        <td>0.551</td>
        <td>0.457</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr align="center">
        <td>13</td>
        <td><a href="https://github.com/DeepGraphLearning/GearNet">ESM-GearNet</a></td>
        <td>AlphaFoldDB (805 K)</td>
        <td>0.894</td>
        <td>0.907</td>
        <td>0.516</td>
        <td>0.301</td>
        <td>0.684</td>
        <td>0.621</td>
        <td>0.506</td>
        <td>0.359</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
</table>


## Related Work 


## Dataset
There are many types of protein datasets available. Most existing datasets are derived from processed PDB files of the original proteins. Currently, CDConv and other methods provide processed datasets (⚠️ note that they are not compatible) that can be downloaded as needed:
1. Enzyme Commission (EC): [Processed By CDConv](https://drive.google.com/file/d/1VEIyBSJbRf9x6k_w4Tqy5SC0G6NWWSWl/view?usp=sharing), [Processed By GearNet](https://zenodo.org/record/6622158/files/EnzymeCommission.zip)
2. Gene Ontology (GO, including GO-BP, GO-MF, GO-CC): [Processed By CDConv](https://drive.google.com/file/d/1H9zv9vjVXFjR0qjKFTBR3nYSQs3ek0hz/view?usp=sharing), [Processed By GearNet](https://zenodo.org/record/6622158/files/GeneOntology.zip)
3.  Protein Fold (including Fold, Family, Superfamily): [Processed By CDConv](https://drive.google.com/file/d/1vEdezR5L44swsw09WFnaA5zFuA1ZEXHI/view?usp=sharing), [Processed By IEConv](http://s3.amazonaws.com/songlabdata/proteindata/data_pytorch/remote_homology.tar.gz)
4. Enzyme Reaction (Reaction) : [Processed By CDConv](https://drive.google.com/file/d/1eL225Y_6TNYQYlVQNdNOsyK9-bSlDno4/view?usp=sharing), [Processed By IEConv](https://drive.google.com/uc?export=download&id=1udP6_90WYkwkvL1LwqIAzf9ibegBJ8rI)
