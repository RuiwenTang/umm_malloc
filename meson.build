project('umm_malloc', 'c', version: '1.0.1', license: 'MIT')


umm_incdir = include_directories('src')
umm_sources = files([
    'src/umm_info.c',
    'src/umm_integrity.c',
    'src/umm_malloc.c',
    'src/umm_poison.c'
   ])

umm_malloc_dep = declare_dependency(
    include_directories: umm_incdir,
    sources: umm_sources,
)