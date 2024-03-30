# X-ray crystallography

X-ray crystallography is by far the most common tool used to determine protein structure.
It provides high resolution of the structure but it does not give information about protein's conformational flexibility.
X-ray crystallography is the experimental science of empirically determining the atomic and molecular structure of a crystal, in which the crystalline structure causes a beam of X-rays to diffract into many specific directions.

!!! quote "Figure 1"

    <figure markdown>
        ![A protein crystal](https://upload.wikimedia.org/wikipedia/commons/0/0e/Protein_crystal.jpg){ width=400 }
    </figure>

    A protein crystal is seen under a microscope.
    Crystals used in X-ray crystallography may be smaller than a millimeter across.

By measuring the angles and intensities of these diffracted beams, a crystallographer can produce a three-dimensional picture of the density of electrons within the crystal.
From this electron density, the positions of the atoms in the crystal can be determined, as well as their chemical bonds.

!!! quote "Figure 2"

    <figure markdown>
        ![Diffraction pattern from a protein crystal](https://upload.wikimedia.org/wikipedia/commons/7/7d/X-ray_diffraction_pattern_3clpro.jpg){ width=500 }
    </figure>

    An X-ray diffraction pattern of a crystallized enzyme.
    The pattern of spots (reflections) and the relative strength of each spot (intensities) can be used to determine the structure of the enzyme.

Since many materials can form crystals—such as salts, metals, minerals, as well as various inorganic, organic, and biological molecules—X-ray crystallography has been fundamental in the development of many scientific fields.
In its first decades of use, this method determined the size of atoms, the lengths and types of chemical bonds, and the atomic-scale differences among various materials.
The method also revealed the structure and function of many biological molecules, including vitamins, drugs, proteins, and nucleic acids such as DNA.
X-ray crystallography is still the primary method for characterizing the atomic structure of new materials and in discerning materials that appear similar to other experiments.

!!! quote "Figure 3A"

    <div id="myoglobin-atomistic-view" class="mol-container"></div>
    <script>
        var uri = 'https://files.rcsb.org/view/3RGK.pdb';
        jQuery.ajax( uri, {
            success: function(data) {
                // https://3dmol.org/doc/GLViewer.html
                let viewer = $3Dmol.createViewer(
                    document.querySelector('#myoglobin-atomistic-view'),
                    { backgroundAlpha: '0.0' }
                );
                viewer.addModel(data, "pdb");
                viewer.setStyle({}, {stick: {}});
                viewer.setStyle({resn: "HEM"}, {stick: {}});
                viewer.setStyle({resi: "200"}, {sphere: {}});
                //viewer.zoomTo({chain: 'A'})
                viewer.setView([ -0.7665464162870579, -31.980985594511658, -1.0271908916093104, -0.8187833451410214, -0.4364964576815298, -0.33783642798767294, -0.526585026363653, -0.6465644595595998 ]);
                viewer.setClickable({}, true, function(atom,viewer,event,container) {
                    console.log(viewer.getView());
                });
                viewer.render();
            },
            error: function(hdr, status, err) {
                console.error( "Failed to load " + uri + ": " + err );
            },
        });
    </script>

    Atomistic representation of myoglobin with the heme group with one oxygen bound.
    PDB ID: [3RGK](https://www.rcsb.org/structure/3RGK)

Such proteins are long, linear molecules with thousands of atoms; yet the relative position of each atom has been determined with sub-atomic resolution by X-ray crystallography.
Since it is difficult to visualize all the atoms at once, the ribbon shows the rough path of the protein's backbone from its N-terminus to its C-terminus.

!!! quote "Figure 3B"

    <div id="myoglobin-view" class="mol-container"></div>
    <script>
        var uri = 'https://files.rcsb.org/view/3RGK.pdb';
        jQuery.ajax( uri, {
            success: function(data) {
                // https://3dmol.org/doc/GLViewer.html
                let viewer = $3Dmol.createViewer(
                    document.querySelector('#myoglobin-view'),
                    { backgroundAlpha: '0.0' }
                );
                viewer.addModel(data, "pdb");
                viewer.setStyle({}, {cartoon: {color: 'spectrum'}});
                viewer.setStyle({resn: "HEM"}, {stick: {}, cartoon: {color: 'spectrum'}});
                viewer.setStyle({resi: "200"}, {sphere: {}});
                //viewer.zoomTo({chain: 'A'})
                viewer.setView([ -0.7665464162870579, -31.980985594511658, -1.0271908916093104, -0.8187833451410214, -0.4364964576815298, -0.33783642798767294, -0.526585026363653, -0.6465644595595998 ]);
                viewer.setClickable({}, true, function(atom,viewer,event,container) {
                    console.log(viewer.getView());
                });
                viewer.render();
            },
            error: function(hdr, status, err) {
                console.error( "Failed to load " + uri + ": " + err );
            },
        });
    </script>

    Ribbon structure of myoglobin with the heme group with one oxygen bound.
    PDB ID: [3RGK](https://www.rcsb.org/structure/3RGK)

Crystal structures of proteins began to be solved in the late 1950s, beginning with the structure of sperm whale myoglobin by Sir John Cowdery Kendrew, for which he shared the Nobel Prize in Chemistry with Max Perutz in 1962.
Since that success, over 130,000 X-ray crystal structures of proteins, nucleic acids, and other biological molecules have been determined.

!!! quote "Figure 4"

    <figure markdown>
        ![](https://upload.wikimedia.org/wikipedia/commons/thumb/7/73/X_ray_diffraction.png/1024px-X_ray_diffraction.png){ width=400 }
    </figure>

    Workflow for solving the structure of a molecule by X-ray crystallography.

<!-- REFERENCES -->
