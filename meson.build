project('nauty', 'c',
  version : '2.7.1',
  default_options : ['warning_level=3'])

lib = library('nauty',
	'traces.c',
	'gtools.c',
	'naututil.c',
	'nautinv.c',
	'gutil1.c',
	'nauty.c',
	'gutil2.c',
	'gtnauty.c',
	'naugroup.c',
	'nautycliquer.c',
	'schreier.c',
	'nautil.c',
	'nausparse.c',
	'naurng.c',
	'naugraph.c',
	version: '2.7.1')

executable('dreadnaut', 'dreadnaut.c', link_with : lib)
