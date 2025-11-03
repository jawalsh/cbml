# What is CBML?

Comic Book Markup Language, or CBML, is an XML vocabulary for encoding multiform documents that are variously called comics, comic books, and “graphic novels” as well as other documents that integrate comics content or that share formal features with comics content.

CBML is based on the [Text Encoding Initiative P5: Guidelines for Electronic Text Encoding and Interchange](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/). The Text Encoding Initiative Guidelines, or simply TEI, provide a scholarly encoding language for the digital representation and analysis of multitudinous and disparate document types: inscriptions and papyri; illuminated manuscripts; authorial holograph manuscripts; correspondence; printed books of prose, verse, and drama; critical and scholarly editions; and born-digital documents. TEI provides general purpose tags for encoding basic structural divisions (e.g., chapters, paragraphs, stanzas and lines of verse, and bibliographic citations) as well as very specific modules targeted at more specific content (e.g., manuscripts, dictionaries, and critical editions).

By using TEI as a foundation for CBML, the standard TEI tags may be used to encode many of the features found in comics and also much of the non-comics content that is so common in comic books. For instance, many comic books contain editorial and news features, prose fiction, fan mail, and advertisements. CBML uses TEI's documented customization mechanisms to add to the standard TEI tag set a number of elements targeted at the distinctive formal features of comics, such as panels, balloons, and narrative captions. CBML also suggests ways to use standard TEI elements and attributes to encode other distinctive features of comics, like “panel groups” and sound effects (POW! THWIP!, FOOM!).

# Comic Book Markup Language: An Introduction and Rationale

A lengthy article, [“Comic Book Markup Language: An Introduction and Rationale”](http://www.digitalhumanities.org/dhq/vol/6/1/000117/000117.html) (Walsh, 2012), published in [Digital Humanities Quarterly](http://digitalhumanities.org/dhq/), provides an introduction to CBML, discusses the rationale and motivations behind the development of CBML, and suggests areas for future work. The article also includes many full-color illustrations and examples.

# Tag Set Documentation

The full [Tag Set Documentation](https://dcl.luddy.indiana.edu/cbml/schema/cbml.html) includes all the TEI elements that are available in the default CBML customization.

## Tag Set Documentation: Custom CBML elements

*   [<cbml:panel\>](https://dcl.luddy.indiana.edu/cbml/schema/cbml.html#TEI.cbml_panel)
*   [<cbml:balloon\>](https://dcl.luddy.indiana.edu/cbml/schema/cbml.html#TEI.cbml_balloon)
*   [<cbml:caption\>](https://dcl.luddy.indiana.edu/cbml/schema/cbml.html#TEI.cbml_caption)

## Tag Set Documentation: Standard TEI elements with CBML exempla

*   [<div\>](https://dcl.luddy.indiana.edu/cbml/schema/cbml.html#TEI.div) for comics panel groups (<div type="panelGrp"\>) and advertisements (<div type="advert"\>)
*   [<sound\>](https://dcl.luddy.indiana.edu/cbml/schema/cbml.html#TEI.sound) for comics “sound effects”

# Downloads

The ODD file was updated and schemas regenerated against the 4.3.0 version (2021-08-31, revision b4f72b1ff) of TEI P5 on 2022-05-24.

[cbml.odd](schema/cbml.odd)

The ODD file that contains the CBML customizations. The ODD file format is used to configure and document TEI customizations such as CBML.

[cbml.rng](https://dcl.luddy.indiana.edu/cbml/schema/cbml.rng)

A Relax NG (XML syntax) schema for CBML, derived from the CBML ODD file.

[cbml.rnc](https://dcl.luddy.indiana.edu/cbml/schema/cbml.rnc)

A Relax NG (compact syntax) schema for CBML, derived from the CBML ODD file.
