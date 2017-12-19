# ISO Schematron 2016 schemas
Unofficial copy of schema(s) for ISO Schematron 2016.

Further contents:

  * A [modified version](svrl_no-xmlschema-ids.rnc) of the SVRL schema that uses xs:NCName instead of xs:ID for all "id" attributes. 
    This version is syntactically and semantically equivalent but avoids problems in several RELAX NG implementations (Schematron/schema#2).