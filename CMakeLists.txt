cmake_minimum_required(VERSION 3.3)

project(BinarySwapNon2 NONE)

include(UseLATEX.cmake)

set(images
  images/binary-swap-1.pdf
  images/binary-swap-2.pdf
  images/binary-swap-3.pdf
  images/naive.pdf

  images/scaling-hdtv.pdf
  images/scaling-8k.pdf
  images/2-3-swap-overhead.pdf
  images/no-compress-hdtv.pdf
  images/no-compress-8k.pdf
  images/vn-vs-smp-hdtv.pdf
  images/vn-vs-smp-8k.pdf
  )

add_latex_document(BinarySwapNon2.tex
  BIBFILES BinarySwapNon2.bib
  IMAGES ${images}
  )
