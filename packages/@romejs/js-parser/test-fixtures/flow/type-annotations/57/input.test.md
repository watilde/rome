# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > type-annotations > 57`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: true
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 41
      index: 41
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 41
          index: 41
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: VariableDeclaration {
        kind: 'var'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 41
            index: 41
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingIdentifier {
              name: 'x'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 35
                  index: 35
                  line: 1
                }
                start: Object {
                  column: 4
                  index: 4
                  line: 1
                }
              }
              meta: PatternMeta {
                definite: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 35
                    index: 35
                    line: 1
                  }
                  start: Object {
                    column: 4
                    index: 4
                    line: 1
                  }
                }
                typeAnnotation: FlowFunctionTypeAnnotation {
                  params: Array []
                  rest: undefined
                  typeParameters: undefined
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 35
                      index: 35
                      line: 1
                    }
                    start: Object {
                      column: 8
                      index: 8
                      line: 1
                    }
                  }
                  returnType: UnionTypeAnnotation {
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 35
                        index: 35
                        line: 1
                      }
                      start: Object {
                        column: 14
                        index: 14
                        line: 1
                      }
                    }
                    types: Array [
                      NumberKeywordTypeAnnotation {
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 20
                            index: 20
                            line: 1
                          }
                          start: Object {
                            column: 14
                            index: 14
                            line: 1
                          }
                        }
                      }
                      FlowFunctionTypeAnnotation {
                        params: Array []
                        rest: undefined
                        typeParameters: undefined
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 35
                            index: 35
                            line: 1
                          }
                          start: Object {
                            column: 23
                            index: 23
                            line: 1
                          }
                        }
                        returnType: StringKeywordTypeAnnotation {
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 35
                              index: 35
                              line: 1
                            }
                            start: Object {
                              column: 29
                              index: 29
                              line: 1
                            }
                          }
                        }
                      }
                    ]
                  }
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 40
                index: 40
                line: 1
              }
              start: Object {
                column: 4
                index: 4
                line: 1
              }
            }
            init: ReferenceIdentifier {
              name: 'fn'
              loc: Object {
                filename: 'input.js'
                identifierName: 'fn'
                end: Object {
                  column: 40
                  index: 40
                  line: 1
                }
                start: Object {
                  column: 38
                  index: 38
                  line: 1
                }
              }
            }
          }
        ]
      }
    }
  ]
}
```
