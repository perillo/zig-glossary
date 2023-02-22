# Zig Glossary

<dl>
  <dt>blank identifier</dt>
  <dd>
    TODO. See ziglang/zig#14694.
  </dd>

  <dt>block</dt>
  <dd>See the Blocks section.</dd>

  <dt>build.zig file</dt>
  <dd>See the Zig Build System  section.</dd>

  <dt>build.zig.zon file</dd>
  <dd>TODO.</dd>

  <dt>container</dt>
  <dd>See the Containers section.</dd>

  <dt>compilation artifact</dt>
  <dd>
    A a static library, a dynamic library, an executable, or an object file.
    Corresponds to <code>std.Build.CompileStep</code>.
  </dd>

  <dt>comptime-known</dt>
  <dd>TODO.</dd>

  <dt>dependency</dt>
  <dd>
    A directed edge between packages. A package may depend on any number of packages.
    A package may be a dependency of any number of packages.
  </dd>

  <dt>identifier syntax</dt>
  <dd>
    <code>@"string"</code>.
    TODO: add more details.
  </dd>

  <dt>module</dt>
  <dd>
    A directory of files, along with a <em>root source file</em> that identifies
    the file referred to when the module is used with <code>`@import`</code>.
  </dd>

  <dt>namespace</dt>
  <dd>Synonym of container.</dd>

  <dt>package</dt>
  <dd>
    A directory of files, uniquely identified by a hash of all files. Packages
    can export any number of compilation artifacts and <em>modules</em>.
  </dd>

  <dt>range syntax</dt>
  <dd>
    <code>start..</code> or <code>start..end</code> inside the <em>for</em> context.
  </dd>

  <dt>result location semantics</dt>
  <dd>See the Result Location Semantics section.</dd>

  <dt>runtime-known</dt>
  <dd>TODO.</dd>

  <dt>shadowing</dt>
  <dd>See the Shadowing section.</dd>

  <dt>slice syntax</dt>
  <dd>
     <code>start..</code>, <code>start..end</code> or <code>start..end :sentinel</code>
     inside the <em>array</em> or <em>slice</em> subscript context.
  </dd>

  <dt>undefined behavior</dt>
  <dd>See the Undefined Behavior section.</dd>

  <dt>unspecified behavior</dt>
  <dd>
    TODO: there is currently no documented unspecified behavior.
    See ziglang/zig#14688 (comment).
  </dd>

  <dt>version</dt>
  <dd>TODO</dd>

  <dt>ZIR</dt>
  <dd>
    Zig Intermediate Representation.
    TODO: add more details.
  </dd>

  <dt>zunit</dt>
  <dd>
    Zig Compilation Unit.
    TODO: add more details.
  </dd>


## Resources

  - https://github.com/ziglang/zig/issues/14307
  - https://github.com/ziglang/zig/pull/14688#discussion_r1113294358
