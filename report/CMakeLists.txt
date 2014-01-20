include(UseLATEX)

add_latex_document(spec.tex BIBFILES pstsp.bib
    DEFAULT_PDF MANGLE_TARGET_NAMES)
