## Metadata MIM extensie

The lineage model provides lineage information as metadata at the property level .

Requierments of the metadata in this respect are the following:

1. metadata at the property level of objecttypes
2. metadata at the instance level of properties
3. metadata can optionally be published
4. metadata model does not have effect on a productmodel


ad 1,2: UML-MIM does not have a construct to bind (meta)data at properties, i.e. attributes or association ends. It is therefore necessary to extend UML-MIM.

ad 3,4: The metadata or in this case lineage model is modelled independently from the product model. Both are 'loosely' connected.

An approach to these requiremnst can be found in the [[Property-Stereotype-for-Metadata]]. This publication presents an UML extension through a stereotype `<<propertyMetadata>>` and a tagged value `metadataType`. An example is presented below.

<figure id="Figure_1">
<img src="media/example_extension.png" alt="">
<figcaption>Example showing use of stereotype <<propertyMetadata>> </figcaption>
</figure>
