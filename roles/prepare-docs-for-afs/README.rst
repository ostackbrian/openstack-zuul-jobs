Prepare built OpenStack docs to be published to the OpenStack AFS cell.

.. zuul:rolevar:: sphinx_build_dir
   :default: doc/build

   Directory relative to zuul_work_dir where Sphinx build output was put.

.. zuul:rolevar:: zuul_work_dir
   :default: {{ zuul.project.src_dir }}

   Directory to build documentation in.

.. zuul:rolevar:: doc_toplevel_dir
   :default: doc

   Directory where the documentation lives, the build documentation is
   in a sub directory called build, by default doc/build.
