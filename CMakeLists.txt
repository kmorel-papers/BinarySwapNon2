cmake_minimum_required(VERSION 3.3)

project(BinarySwapNon2 NONE)

include(UseLATEX.cmake)

set(images
  images/scaling-hdtv.pdf
  images/scaling-8k.pdf
  )

add_latex_document(BinarySwapNon2.tex
  BIBFILES BinarySwapNon2.bib
  IMAGES ${images}
  )
