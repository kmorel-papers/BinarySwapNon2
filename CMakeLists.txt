cmake_minimum_required(VERSION 3.3)

project(BinarySwapNon2 NONE)

include(UseLATEX.cmake)

set(images
  images/binary-swap-1.pdf
  images/binary-swap-2.pdf
  images/binary-swap-3.pdf
  images/naive.pdf
  images/234-composite-6-proc.pdf
  images/telescoping-7-proc.pdf
  images/remainder-1.pdf
  images/remainder-2.pdf
  images/2-3-swap-1.pdf
  images/2-3-swap-2.pdf

  images/render-example.png

  images/scaling-hdtv.pdf
  images/scaling-8k.pdf
  images/2-3-swap-overhead.pdf
  images/no-compress-hdtv.pdf
  images/no-compress-8k.pdf
  images/vn-vs-smp-hdtv.pdf
  images/vn-vs-smp-8k.pdf
  images/gather-hdtv.pdf
  images/gather-8k.pdf
  )

add_latex_document(BinarySwapNon2.tex
  BIBFILES BinarySwapNon2.bib
  IMAGES ${images}
  )
