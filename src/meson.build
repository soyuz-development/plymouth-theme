plymouth_themes = [
  'soyuz-bgrt',
]

foreach plymouth_theme: plymouth_themes
  if not get_option(plymouth_theme)
    message('skip plymouth_theme ' + plymouth_theme)
    continue
  endif

  message('build plymouth_theme ' + plymouth_theme)
  subdir(plymouth_theme)

endforeach
