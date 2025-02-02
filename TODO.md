* [Doc/extending/embedding.rst:283](Doc/extending/embedding.rst#L283): threads, code examples do not really behave well if errors happen
* [Doc/library/zoneinfo.rst:220](Doc/library/zoneinfo.rst#L220): Add "See `cache_behavior`_" reference when that section is ready.
* [Doc/library/zoneinfo.rst:239](Doc/library/zoneinfo.rst#L239): Add "See `cache_behavior`_" reference when that section is ready.
* [Doc/whatsnew/3.8.rst:189](Doc/whatsnew/3.8.rst#L189): Pablo will sprint on docs at PyCon US 2019.
* [Include/internal/mimalloc/mimalloc/internal.h:661](Include/internal/mimalloc/mimalloc/internal.h#L661): check if `next` is `page->block_size` aligned?
* [Include/internal/pycore_object.h:264](Include/internal/pycore_object.h#L264): implement Py_DECREF specializations for Py_GIL_DISABLED build
* [Include/internal/pycore_runtime.h:138](Include/internal/pycore_runtime.h#L138): Given interp_main, it may be possible to kill this ref */
* [Lib/asyncio/staggered.py:65](Lib/asyncio/staggered.py#L65): when we have aiter() and anext(), allow async iterables in coro_fns.
* [Lib/idlelib/autocomplete_w.py:498](Lib/idlelib/autocomplete_w.py#L498): autocomplete/w htest here
* [Lib/idlelib/config.py:601](Lib/idlelib/config.py#L601): = dict(sorted([(v-event, keys), ...]))?
* [Lib/idlelib/debugger.py:602](Lib/idlelib/debugger.py#L602): htest?
* [Lib/idlelib/editor.py:995](Lib/idlelib/editor.py#L995): move to iomenu.
* [Lib/idlelib/idle_test/test_config.py:376](Lib/idlelib/idle_test/test_config.py#L376): finish.
* [Lib/idlelib/idle_test/test_config.py:766](Lib/idlelib/idle_test/test_config.py#L766): test that save_all calls usercfg Saves.
* [Lib/idlelib/idle_test/test_sidebar.py:258](Lib/idlelib/idle_test/test_sidebar.py#L258): Re-work these tests or remove them from the test suite.
* [Lib/idlelib/mainmenu.py:20](Lib/idlelib/mainmenu.py#L20): Make this more robust
* [Lib/idlelib/runscript.py:10](Lib/idlelib/runscript.py#L10): Specify command line arguments in a dialog box.
* [Lib/idlelib/sidebar.py:34](Lib/idlelib/sidebar.py#L34): use also in codecontext.py
* [Lib/mailbox.py:431](Lib/mailbox.py#L431): check if flags are valid standard flag characters?
* [Lib/mailbox.py:438](Lib/mailbox.py#L438): check that flag is a valid standard flag character?
* [Lib/mimetypes.py:121](Lib/mimetypes.py#L121): Deprecate accepting file paths (in particular path-like objects).
* [Lib/multiprocessing/synchronize.py:24](Lib/multiprocessing/synchronize.py#L24): Do any platforms still lack a functioning sem_open?
* [Lib/numbers.py:6](Lib/numbers.py#L6): Fill out more detailed documentation on the operators."""
* [Lib/runpy.py:64](Lib/runpy.py#L64): Replace these helpers with importlib._bootstrap_external functions.
* [Lib/test/_test_multiprocessing.py:5096](Lib/test/_test_multiprocessing.py#L5096): add more tests for deliver/answer challenge.
* [Lib/test/_test_multiprocessing.py:6299](Lib/test/_test_multiprocessing.py#L6299): fix https://bugs.python.org/issue35919
* [Lib/test/libregrtest/tsan.py:5](Lib/test/libregrtest/tsan.py#L5): enable more of test_capi once bugs are fixed (GH-116908, GH-116909).
* [Lib/test/support/asynchat.py:1](Lib/test/support/asynchat.py#L1): This module was deprecated and removed from CPython 3.12
* [Lib/test/support/asyncore.py:1](Lib/test/support/asyncore.py#L1): This module was deprecated and removed from CPython 3.12
* [Lib/test/test_asyncio/test_events.py:2656](Lib/test/test_asyncio/test_events.py#L2656): Use assertLess etc.
* [Lib/test/test_c_locale_coercion.py:36](Lib/test/test_c_locale_coercion.py#L36): Once https://bugs.python.org/issue30672 is addressed, we'll be
* [Lib/test/test_c_locale_coercion.py:48](Lib/test/test_c_locale_coercion.py#L48): Work out a robust dynamic test for this that doesn't rely on
* [Lib/test/test_capi/test_codecs.py:118](Lib/test/test_capi/test_codecs.py#L118): Test PyUnicode_DecodeUTF8() with NULL as data and
* [Lib/test/test_capi/test_codecs.py:139](Lib/test/test_capi/test_codecs.py#L139): Test PyUnicode_DecodeUTF8Stateful() with NULL as data and
* [Lib/test/test_capi/test_codecs.py:141](Lib/test/test_capi/test_codecs.py#L141): Test PyUnicode_DecodeUTF8Stateful() with NULL as the address of
* [Lib/test/test_capi/test_codecs.py:18](Lib/test/test_capi/test_codecs.py#L18): Test the following functions:
* [Lib/test/test_capi/test_codecs.py:197](Lib/test/test_capi/test_codecs.py#L197): Test PyUnicode_DecodeUTF16() with NULL as data and
* [Lib/test/test_capi/test_codecs.py:241](Lib/test/test_capi/test_codecs.py#L241): Test PyUnicode_DecodeUTF16Stateful() with NULL as data and
* [Lib/test/test_capi/test_codecs.py:243](Lib/test/test_capi/test_codecs.py#L243): Test PyUnicode_DecodeUTF16Stateful() with NULL as the address of
* [Lib/test/test_capi/test_codecs.py:295](Lib/test/test_capi/test_codecs.py#L295): Test PyUnicode_DecodeUTF32() with NULL as data and
* [Lib/test/test_capi/test_codecs.py:345](Lib/test/test_capi/test_codecs.py#L345): Test PyUnicode_DecodeUTF32Stateful() with NULL as data and
* [Lib/test/test_capi/test_codecs.py:347](Lib/test/test_capi/test_codecs.py#L347): Test PyUnicode_DecodeUTF32Stateful() with NULL as the address of
* [Lib/test/test_capi/test_codecs.py:370](Lib/test/test_capi/test_codecs.py#L370): Test PyUnicode_DecodeLatin1() with NULL as data and
* [Lib/test/test_capi/test_codecs.py:397](Lib/test/test_capi/test_codecs.py#L397): Test PyUnicode_DecodeASCII() with NULL as data and
* [Lib/test/test_capi/test_codecs.py:431](Lib/test/test_capi/test_codecs.py#L431): Test PyUnicode_DecodeCharmap() with NULL as data and
* [Lib/test/test_capi/test_codecs.py:472](Lib/test/test_capi/test_codecs.py#L472): Test PyUnicode_DecodeUnicodeEscape() with NULL as data and
* [Lib/test/test_capi/test_codecs.py:508](Lib/test/test_capi/test_codecs.py#L508): Test PyUnicode_DecodeRawUnicodeEscape() with NULL as data and
* [Lib/test/test_capi/test_codecs.py:75](Lib/test/test_capi/test_codecs.py#L75): Test PyUnicode_Decode() with NULL as data and
* [Lib/test/test_capi/test_file.py:298](Lib/test/test_capi/test_file.py#L298): Test Py_UniversalNewlineFgets()
* [Lib/test/test_capi/test_function.py:310](Lib/test/test_capi/test_function.py#L310): test PyFunction_New()
* [Lib/test/test_capi/test_function.py:311](Lib/test/test_capi/test_function.py#L311): test PyFunction_NewWithQualName()
* [Lib/test/test_capi/test_function.py:312](Lib/test/test_capi/test_function.py#L312): test PyFunction_SetVectorcall()
* [Lib/test/test_capi/test_function.py:313](Lib/test/test_capi/test_function.py#L313): test PyFunction_GetAnnotations()
* [Lib/test/test_capi/test_function.py:314](Lib/test/test_capi/test_function.py#L314): test PyFunction_SetAnnotations()
* [Lib/test/test_capi/test_function.py:315](Lib/test/test_capi/test_function.py#L315): test PyClassMethod_New()
* [Lib/test/test_capi/test_function.py:316](Lib/test/test_capi/test_function.py#L316): test PyStaticMethod_New()
* [Lib/test/test_capi/test_import.py:374](Lib/test/test_capi/test_import.py#L374): test PyImport_GetImporter()
* [Lib/test/test_capi/test_import.py:375](Lib/test/test_capi/test_import.py#L375): test PyImport_ReloadModule()
* [Lib/test/test_capi/test_import.py:376](Lib/test/test_capi/test_import.py#L376): test PyImport_ExtendInittab()
* [Lib/test/test_capi/test_run.py:19](Lib/test/test_capi/test_run.py#L19): Test the following functions:
* [Lib/test/test_capi/test_sys.py:15](Lib/test/test_capi/test_sys.py#L15): Test the following functions:
* [Lib/test/test_capi/test_unicode.py:122](Lib/test/test_capi/test_unicode.py#L122): Test PyUnicode_WriteChar() with non-modifiable and legacy
* [Lib/test/test_capi/test_unicode.py:148](Lib/test/test_capi/test_unicode.py#L148): Test PyUnicode_Resize() with non-modifiable and legacy unicode
* [Lib/test/test_capi/test_unicode.py:1721](Lib/test/test_capi/test_unicode.py#L1721): Test PyUnicode_CopyCharacters() with non-unicode and
* [Lib/test/test_capi/test_unicode.py:175](Lib/test/test_capi/test_unicode.py#L175): Test PyUnicode_Append() with modifiable unicode
* [Lib/test/test_capi/test_unicode.py:177](Lib/test/test_capi/test_unicode.py#L177): Check reference counts.
* [Lib/test/test_capi/test_unicode.py:202](Lib/test/test_capi/test_unicode.py#L202): Test PyUnicode_AppendAndDel() with modifiable unicode
* [Lib/test/test_capi/test_unicode.py:204](Lib/test/test_capi/test_unicode.py#L204): Check reference counts.
* [Lib/test/test_capi/test_unicode.py:92](Lib/test/test_capi/test_unicode.py#L92): Test PyUnicode_Fill() with non-modifiable unicode.
* [Lib/test/test_code.py:421](Lib/test/test_code.py#L421): remove in 3.14
* [Lib/test/test_curses.py:1002](Lib/test/test_curses.py#L1002): key_name()
* [Lib/test/test_curses.py:121](Lib/test/test_curses.py#L121): Should be called before initscr() or newterm() are called.
* [Lib/test/test_curses.py:122](Lib/test/test_curses.py#L122): nofilter()
* [Lib/test/test_curses.py:127](Lib/test/test_curses.py#L127): Should be called before initscr() or newterm() are called.
* [Lib/test/test_curses.py:128](Lib/test/test_curses.py#L128): use_tioctl()
* [Lib/test/test_curses.py:344](Lib/test/test_curses.py#L344): Test with real input by writing to master fd.
* [Lib/test/test_curses.py:364](Lib/test/test_curses.py#L364): Test with real input by writing to master fd.
* [Lib/test/test_curses.py:455](Lib/test/test_curses.py#L455): attr_get(), attr_set(), ...
* [Lib/test/test_curses.py:652](Lib/test/test_curses.py#L652): wunctrl()
* [Lib/test/test_curses.py:710](Lib/test/test_curses.py#L710): term_attrs(), erasewchar(), killwchar()
* [Lib/test/test_dataclasses/__init__.py:3750](Lib/test/test_dataclasses/__init__.py#L3750): This test is for a kinda-buggy behavior.
* [Lib/test/test_ftplib.py:358](Lib/test/test_ftplib.py#L358): SSLError does not expose alert information
* [Lib/test/test_inspect/test_inspect.py:3173](Lib/test/test_inspect/test_inspect.py#L3173): Support type.
* [Lib/test/test_inspect/test_inspect.py:4129](Lib/test/test_inspect/test_inspect.py#L4129): Support BuiltinMethodType
* [Lib/test/test_inspect/test_inspect.py:4138](Lib/test/test_inspect/test_inspect.py#L4138): Support MethodWrapperType
* [Lib/test/test_inspect/test_inspect.py:4142](Lib/test/test_inspect/test_inspect.py#L4142): Test ClassMethodDescriptorType
* [Lib/test/test_inspect/test_inspect.py:4156](Lib/test/test_inspect/test_inspect.py#L4156): Support WrapperDescriptorType
* [Lib/test/test_inspect/test_inspect.py:4214](Lib/test/test_inspect/test_inspect.py#L4214): Support type.
* [Lib/test/test_io.py:3831](Lib/test/test_io.py#L3831): txt.reconfigure(encoding='utf-8\0')
* [Lib/test/test_io.py:3832](Lib/test/test_io.py#L3832): txt.reconfigure(encoding='nonexisting')
* [Lib/test/test_io.py:3838](Lib/test/test_io.py#L3838): txt.reconfigure(errors='ignore\0')
* [Lib/test/test_io.py:3839](Lib/test/test_io.py#L3839): txt.reconfigure(errors='nonexisting')
* [Lib/test/test_io.py:3847](Lib/test/test_io.py#L3847): Should fail in C too.
* [Lib/test/test_io.py:3851](Lib/test/test_io.py#L3851): Use __bool__(), not __index__().
* [Lib/test/test_logging.py:6493](Lib/test/test_logging.py#L6493): Test for utc=False.
* [Lib/test/test_logging.py:6533](Lib/test/test_logging.py#L6533): Test for utc=False.
* [Lib/test/test_peg_generator/test_first_sets.py:235](Lib/test/test_peg_generator/test_first_sets.py#L235): Validate this
* [Lib/test/test_poplib.py:186](Lib/test/test_poplib.py#L186): SSLError does not expose alert information
* [Lib/test/test_runpy.py:192](Lib/test/test_runpy.py#L192): Use self.addCleanup to get rid of a lot of try-finally blocks
* [Lib/test/test_ssl.py:3059](Lib/test/test_ssl.py#L3059): fix TLSv1.3 once SSLContext can restrict signature
* [Lib/test/test_ssl.py:4289](Lib/test/test_ssl.py#L4289): sessions aren't compatible with TLSv1.3 yet
* [Lib/test/test_ssl.py:4348](Lib/test/test_ssl.py#L4348): session reuse does not work with TLSv1.3
* [Lib/test/test_sys.py:1786](Lib/test/test_sys.py#L1786): add check that forces the presence of wchar_t representation
* [Lib/test/test_sys.py:1787](Lib/test/test_sys.py#L1787): add check that forces layout of unicodefields
* [Lib/test/test_trace.py:431](Lib/test/test_trace.py#L431): Skip tests that do mess with sys.settrace when
* [Lib/tkinter/__init__.py:2158](Lib/tkinter/__init__.py#L2158): deprecate
* [Lib/tkinter/__init__.py:2161](Lib/tkinter/__init__.py#L2161): deprecate
* [Lib/tkinter/__init__.py:506](Lib/tkinter/__init__.py#L506): Add deprecation warning
* [Lib/tkinter/__init__.py:522](Lib/tkinter/__init__.py#L522): Add deprecation warning
* [Lib/tkinter/__init__.py:541](Lib/tkinter/__init__.py#L541): Add deprecation warning
* [Lib/types.py:240](Lib/types.py#L240): Implement this in C.
* [Lib/types.py:295](Lib/types.py#L295): Implement this in C.
* [Lib/xml/etree/ElementTree.py:1260](Lib/xml/etree/ElementTree.py#L1260): Emit a ResourceWarning if it was not explicitly closed.
* [Lib/zoneinfo/_zoneinfo.py:588](Lib/zoneinfo/_zoneinfo.py#L588): These are not actually epoch dates as they are expressed in local time
* [Mac/BuildScript/build-installer.py:1342](Mac/BuildScript/build-installer.py#L1342): make this more robust!  test_sysconfig_module of
* [Modules/_decimal/libmpdec/mpdecimal.c:6644](Modules/_decimal/libmpdec/mpdecimal.c#L6644): Implement algorithm for computing exact powers from decimal.py.
* [Modules/_io/bufferedio.c:1422](Modules/_io/bufferedio.c#L1422): align on block boundary and read buffer if needed? */
* [Modules/_io/bufferedio.c:2200](Modules/_io/bufferedio.c#L2200): sanity check (remaining >= 0) */
* [Modules/_io/bufferedio.c:763](Modules/_io/bufferedio.c#L763): sanity check (err->written >= 0) */
* [Modules/_io/iobase.c:922](Modules/_io/iobase.c#L922): allocate a bytes object directly instead and manually construct
* [Modules/_pickle.c:2350](Modules/_pickle.c#L2350): It would be better to use a memoryview with a linked
* [Modules/_ssl.c:1940](Modules/_ssl.c#L1940): include SSL_get_peer_certificate() for server-side sockets */
* [Modules/_ssl.c:4033](Modules/_ssl.c#L4033): It would be nice to move _ctypes_add_traceback() into the
* [Modules/posixmodule.c:7977](Modules/posixmodule.c#L7977): Consider making an `os` module API to return the current number
* [Modules/sha2module.c:50](Modules/sha2module.c#L50): Get rid of int digestsize in favor of Hacl state info?
* [Objects/dictobject.c:2005](Objects/dictobject.c#L2005): Try reusing oldkeys when reimplement odict.
* [Objects/dictobject.c:2271](Objects/dictobject.c#L2271): Thread safety
* [Objects/enumobject.c:100](Objects/enumobject.c#L100): Use AC when bpo-43447 is supported
* [Objects/genericaliasobject.c:296](Objects/genericaliasobject.c#L296): Add test
* [Objects/genericaliasobject.c:522](Objects/genericaliasobject.c#L522): Hash in the hash for the origin
* [Objects/mimalloc/alloc-aligned.c:121](Objects/mimalloc/alloc-aligned.c#L121): inline _mi_page_malloc
* [Objects/mimalloc/arena.c:763](Objects/mimalloc/arena.c#L763): can we avoid allocating from the OS?
* [Objects/mimalloc/arena.c:776](Objects/mimalloc/arena.c#L776): or get the current numa node if -1? (now it allows anyone to allocate on -1)
* [Objects/mimalloc/bitmap.c:70](Objects/mimalloc/bitmap.c#L70): use weak cas here?
* [Objects/mimalloc/heap.c:265](Objects/mimalloc/heap.c#L265): copy full empty heap instead?
* [Objects/mimalloc/options.c:300](Objects/mimalloc/options.c#L300): use mi_out_stderr for stderr?
* [Objects/mimalloc/options.c:500](Objects/mimalloc/options.c#L500): implement ourselves to reduce dependencies on the C runtime
* [Objects/mimalloc/page.c:270](Objects/mimalloc/page.c#L270): push on full queue immediately if it is full?
* [Objects/mimalloc/prim/unix/prim.c:135](Objects/mimalloc/prim/unix/prim.c#L135): can we query the OS for this?
* [Objects/mimalloc/prim/unix/prim.c:447](Objects/mimalloc/prim/unix/prim.c#L447): does `mbind` work correctly for huge OS pages? should we
* [Objects/mimalloc/prim/unix/prim.c:524](Objects/mimalloc/prim/unix/prim.c#L524): DragonFly does not seem to provide any userland means to get this information.
* [Objects/mimalloc/segment-map.c:84](Objects/mimalloc/segment-map.c#L84): maintain max/min allocated range for efficiency for more efficient rejection of invalid pointers?
* [Objects/obmalloc.c:1160](Objects/obmalloc.c#L1160): Fix me
* [PC/launcher2.c:2387](PC/launcher2.c#L2387): Do we want to display these?
* [PC/layout/support/props.py:85](PC/layout/support/props.py#L85): Filter contents of props file according to included/excluded items
* [Parser/lexer/lexer.c:1319](Parser/lexer/lexer.c#L1319): This is a bit of a hack, but it works for now. We need to find a better way to handle
* [Parser/lexer/lexer.c:959](Parser/lexer/lexer.c#L959): Check this
* [Parser/lexer/state.h:121](Parser/lexer/state.h#L121): Factor this into its own thing
* [Parser/pegen.h:361](Parser/pegen.h#L361): move to the correct place in this file
* [Python/ceval.c:250](Python/ceval.c#L250): Parse an int and all that
* [Python/gc_free_threading.c:1154](Python/gc_free_threading.c#L1154): move to pycore_runtime_init.h once the incremental GC lands.
* [Python/gc_free_threading.c:1498](Python/gc_free_threading.c#L1498): Use Py_ssize_t for the generation count.
* [Python/optimizer.c:1137](Python/optimizer.c#L1137): Parse an int and all that
* [Python/optimizer.c:504](Python/optimizer.c#L504): Parse an int and all that
* [Python/optimizer.c:789](Python/optimizer.c#L789): Reason about this -- is it better to bail or not?
* [Python/optimizer_analysis.c:45](Python/optimizer_analysis.c#L45): Parse an int and all that
* [Python/optimizer_symbols.c:36](Python/optimizer_symbols.c#L36): Parse an int and all that
* [Python/perf_trampoline.c:295](Python/perf_trampoline.c#L295): Check the effect of alignment of the code chunks. Initial investigation
* [Python/pythonrun.c:9](Python/pythonrun.c#L9): Cull includes following phase split */
* [Python/sysmodule.c:2827](Python/sysmodule.c#L2827): we can reach this if warnoptions is NULL in the main
* [Python/sysmodule.c:2927](Python/sysmodule.c#L2927): we can reach this if xoptions is NULL in the main
* [Tools/build/deepfreeze.py:389](Tools/build/deepfreeze.py#L389): The above tuple should be a frozenset")
* [Tools/build/freeze_modules.py:520](Tools/build/freeze_modules.py#L520): Is this necessary any more?
* [Tools/build/freeze_modules.py:530](Tools/build/freeze_modules.py#L530): Use more obvious markers, e.g.
* [Tools/cases_generator/README.md:56](Tools/cases_generator/README.md#L56): ` comments.
* [Tools/cases_generator/lexer.py:112](Tools/cases_generator/lexer.py#L112): escape sequence
* [Tools/cases_generator/lexer.py:366](Tools/cases_generator/lexer.py#L366): dedent > 0
* [Tools/cases_generator/plexer.py:33](Tools/cases_generator/plexer.py#L33): Return synthetic EOF token instead of None?
* [Tools/clinic/libclinic/block_parser.py:68](Tools/clinic/libclinic/block_parser.py#L68): Very dynamic; probably untypeable in its current form?
* [Tools/gdb/libpython.py:1584](Tools/gdb/libpython.py#L1584): repr() puts everything on one line; pformat can be nicer, but
* [Tools/msi/bundle/bootstrap/PythonBootstrapperApplication.cpp:2412](Tools/msi/bundle/bootstrap/PythonBootstrapperApplication.cpp#L2412): This doesn't work
* [Tools/msi/bundle/bootstrap/PythonBootstrapperApplication.cpp:329](Tools/msi/bundle/bootstrap/PythonBootstrapperApplication.cpp#L329): Check whether directory exists and contains another installation
* [Tools/peg_generator/peg_extension/peg_extension.c:127](Tools/peg_generator/peg_extension/peg_extension.c#L127): Write to Python's sys.stdout instead of C's stdout.
* [Tools/peg_generator/pegen/ast_dump.py:6](Tools/peg_generator/pegen/ast_dump.py#L6): Remove the above-described hack.
* [Tools/peg_generator/pegen/build.py:22](Tools/peg_generator/pegen/build.py#L22): install `types-setuptools` and remove this alias
* [Tools/peg_generator/pegen/build.py:319](Tools/peg_generator/pegen/build.py#L319): skip_actions
* [Tools/peg_generator/pegen/grammar.py:256](Tools/peg_generator/pegen/grammar.py#L256): Decide whether to use [X] or X? based on type of X
* [Tools/peg_generator/pegen/grammar.py:283](Tools/peg_generator/pegen/grammar.py#L283): Decide whether to use (X)* or X* based on type of X
* [Tools/peg_generator/pegen/grammar.py:296](Tools/peg_generator/pegen/grammar.py#L296): Decide whether to use (X)+ or X+ based on type of X
* [Tools/peg_generator/pegen/parser_generator.py:178](Tools/peg_generator/pegen/parser_generator.py#L178): Pick a nicer name.
* [Tools/peg_generator/pegen/sccutils.py:124](Tools/peg_generator/pegen/sccutils.py#L124): Make this not quadratic.
* [Tools/peg_generator/pegen/sccutils.py:86](Tools/peg_generator/pegen/sccutils.py#L86): Use a faster algorithm?
* [Tools/peg_generator/pegen/testutil.py:94](Tools/peg_generator/pegen/testutil.py#L94): express that using a Protocol.
* [Tools/scripts/summarize_stats.py:35](Tools/scripts/summarize_stats.py#L35): Check for parity
* [Tools/wasm/emscripten/web_example/python.html:189](Tools/wasm/emscripten/web_example/python.html#L189): Handle ANSI escape sequences
* [Tools/wasm/wasm_build.py:383](Tools/wasm/wasm_build.py#L383): look for recent node
* [configure.ac:1638](configure.ac#L1638): support other WASI runtimes
