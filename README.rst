================================================
 Implement ``play-sound-internal`` for Mac OS X
================================================

To enable it place this snippet::

  (unless (and (fboundp 'play-sound-internal)
               (subrp (symbol-function 'play-sound-internal)))
    (require 'play-sound))

in your init file.
