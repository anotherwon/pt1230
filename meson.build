project('pt1230', 'c',
  default_options : ['c_std=c99',
                     'warning_level=3'])

executable('pt1230',
           'pt1230.c',
           install : true)

executable('textlabel',
           'textlabel.c',
           dependencies : [
              dependency('fontconfig')],
           install : true)

executable('line2bitmap',
           'line2bitmap.c',
           install : true)
