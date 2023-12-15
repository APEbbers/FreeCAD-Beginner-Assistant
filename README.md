# FreeCAD-Self-Teaching
Gives feedback/hints with recommendations to parts created in FreeCAD Part Design. Aimes to increase the quality of community-created Part Design models.

Analyses a FreeCAD FCStd File containing at least one Part Design Body and gives hints, based on best practices, to the creator of the Part Design bodies.

This project is related to the FreeCAD-Tutorial-Generator and the FCViewer Platform and adds to the ecosystem of teaching resources for Beginner FreeCAD Users.

Part Design best practices:
- Follow the plane, sketch, feature workflow
- only use one closed wire per sketch
- first create all additive features and then all subtractive features, if possible
- do not attach sketches to Topological Elements (Vertexes, Edges, Faces), always use Elements that dont change, such as the Origin for reference.
- Use Fillets and Chamfers as the last features
(More best practices to be added)
