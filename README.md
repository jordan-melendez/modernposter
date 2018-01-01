## modernposter - A modern LaTeX poster theme

This class extends the a0poster class in that it adds support to position textboxes in a two-column layout. The color scheme is inspired by the [metropolis beamer theme](https://github.com/matze/mtheme). 

Below you can find a preview of the demo:

![Preview](https://i.imgur.com/XUr9a5U.jpg)

## Usage

Below you can find a toy example, demonstrating how to use modernposter

```latex
\documentclass{modernposter}

\title{This is a Modernposter Demo}
\author{Firstname Lastname}
\email{firstname.lastname@domain.com} 

\begin{document}
  \maketitle  

  \begin{postercolumn}
    \posterbox{Introduction}{ 
      $\dots$
    }
  \end{postercolumn} 
  \begin{postercolumn}
    \doubleposterbox[0.6]
      {Problem Statement}{
       
      }
      {\highlight{Results}}{ 
      
      }
  \end{postercolumn}
\end{document}
```

## Authors
The code was written by David Derler. He can be contacted via [modernposter@derler.info](mailto:modernposter@derler.info).

## License
The code is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/).