# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > predicates > 6`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
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
      column: 0
      index: 87
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    FlowDeclareFunction {
      id: BindingIdentifier {
        name: 'my_filter'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 86
            index: 86
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        meta: PatternMeta {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 86
              index: 86
              line: 1
            }
            start: Object {
              column: 0
              index: 0
              line: 1
            }
          }
          typeAnnotation: FlowFunctionTypeAnnotation {
            rest: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 86
                index: 86
                line: 1
              }
              start: Object {
                column: 0
                index: 0
                line: 1
              }
            }
            typeParameters: FlowTypeParameterDeclaration {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 42
                  index: 42
                  line: 1
                }
                start: Object {
                  column: 26
                  index: 26
                  line: 1
                }
              }
              params: Array [
                FlowTypeParameter {
                  name: 'T'
                  bound: undefined
                  default: undefined
                  variance: undefined
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 28
                      index: 28
                      line: 1
                    }
                    start: Object {
                      column: 27
                      index: 27
                      line: 1
                    }
                  }
                }
                FlowTypeParameter {
                  name: 'P'
                  default: undefined
                  variance: undefined
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 41
                      index: 41
                      line: 1
                    }
                    start: Object {
                      column: 30
                      index: 30
                      line: 1
                    }
                  }
                  bound: FlowGenericTypeAnnotation {
                    id: ReferenceIdentifier {
                      name: '$Pred'
                      loc: Object {
                        filename: 'input.js'
                        identifierName: '$Pred'
                        end: Object {
                          column: 38
                          index: 38
                          line: 1
                        }
                        start: Object {
                          column: 33
                          index: 33
                          line: 1
                        }
                      }
                    }
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 41
                        index: 41
                        line: 1
                      }
                      start: Object {
                        column: 33
                        index: 33
                        line: 1
                      }
                    }
                    typeParameters: FlowTypeParameterInstantiation {
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 41
                          index: 41
                          line: 1
                        }
                        start: Object {
                          column: 38
                          index: 38
                          line: 1
                        }
                      }
                      params: Array [
                        NumericLiteralTypeAnnotation {
                          value: 1
                          format: undefined
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 40
                              index: 40
                              line: 1
                            }
                            start: Object {
                              column: 39
                              index: 39
                              line: 1
                            }
                          }
                        }
                      ]
                    }
                  }
                }
              ]
            }
            returnType: FlowGenericTypeAnnotation {
              id: ReferenceIdentifier {
                name: 'Array'
                loc: Object {
                  filename: 'input.js'
                  identifierName: 'Array'
                  end: Object {
                    column: 69
                    index: 69
                    line: 1
                  }
                  start: Object {
                    column: 64
                    index: 64
                    line: 1
                  }
                }
              }
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 85
                  index: 85
                  line: 1
                }
                start: Object {
                  column: 64
                  index: 64
                  line: 1
                }
              }
              typeParameters: FlowTypeParameterInstantiation {
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 85
                    index: 85
                    line: 1
                  }
                  start: Object {
                    column: 69
                    index: 69
                    line: 1
                  }
                }
                params: Array [
                  FlowGenericTypeAnnotation {
                    id: ReferenceIdentifier {
                      name: '$Refine'
                      loc: Object {
                        filename: 'input.js'
                        identifierName: '$Refine'
                        end: Object {
                          column: 77
                          index: 77
                          line: 1
                        }
                        start: Object {
                          column: 70
                          index: 70
                          line: 1
                        }
                      }
                    }
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 84
                        index: 84
                        line: 1
                      }
                      start: Object {
                        column: 70
                        index: 70
                        line: 1
                      }
                    }
                    typeParameters: FlowTypeParameterInstantiation {
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 84
                          index: 84
                          line: 1
                        }
                        start: Object {
                          column: 77
                          index: 77
                          line: 1
                        }
                      }
                      params: Array [
                        FlowGenericTypeAnnotation {
                          id: ReferenceIdentifier {
                            name: 'T'
                            loc: Object {
                              filename: 'input.js'
                              identifierName: 'T'
                              end: Object {
                                column: 79
                                index: 79
                                line: 1
                              }
                              start: Object {
                                column: 78
                                index: 78
                                line: 1
                              }
                            }
                          }
                          typeParameters: undefined
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 79
                              index: 79
                              line: 1
                            }
                            start: Object {
                              column: 78
                              index: 78
                              line: 1
                            }
                          }
                        }
                        FlowGenericTypeAnnotation {
                          id: ReferenceIdentifier {
                            name: 'P'
                            loc: Object {
                              filename: 'input.js'
                              identifierName: 'P'
                              end: Object {
                                column: 81
                                index: 81
                                line: 1
                              }
                              start: Object {
                                column: 80
                                index: 80
                                line: 1
                              }
                            }
                          }
                          typeParameters: undefined
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 81
                              index: 81
                              line: 1
                            }
                            start: Object {
                              column: 80
                              index: 80
                              line: 1
                            }
                          }
                        }
                        NumericLiteralTypeAnnotation {
                          value: 1
                          format: undefined
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 83
                              index: 83
                              line: 1
                            }
                            start: Object {
                              column: 82
                              index: 82
                              line: 1
                            }
                          }
                        }
                      ]
                    }
                  }
                ]
              }
            }
            params: Array [
              FlowFunctionTypeParam {
                name: Identifier {
                  name: 'v'
                  loc: Object {
                    filename: 'input.js'
                    identifierName: 'v'
                    end: Object {
                      column: 44
                      index: 44
                      line: 1
                    }
                    start: Object {
                      column: 43
                      index: 43
                      line: 1
                    }
                  }
                }
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 54
                    index: 54
                    line: 1
                  }
                  start: Object {
                    column: 43
                    index: 43
                    line: 1
                  }
                }
                meta: PatternMeta {
                  optional: false
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 54
                      index: 54
                      line: 1
                    }
                    start: Object {
                      column: 43
                      index: 43
                      line: 1
                    }
                  }
                  typeAnnotation: FlowGenericTypeAnnotation {
                    id: ReferenceIdentifier {
                      name: 'Array'
                      loc: Object {
                        filename: 'input.js'
                        identifierName: 'Array'
                        end: Object {
                          column: 51
                          index: 51
                          line: 1
                        }
                        start: Object {
                          column: 46
                          index: 46
                          line: 1
                        }
                      }
                    }
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 54
                        index: 54
                        line: 1
                      }
                      start: Object {
                        column: 46
                        index: 46
                        line: 1
                      }
                    }
                    typeParameters: FlowTypeParameterInstantiation {
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 54
                          index: 54
                          line: 1
                        }
                        start: Object {
                          column: 51
                          index: 51
                          line: 1
                        }
                      }
                      params: Array [
                        FlowGenericTypeAnnotation {
                          id: ReferenceIdentifier {
                            name: 'T'
                            loc: Object {
                              filename: 'input.js'
                              identifierName: 'T'
                              end: Object {
                                column: 53
                                index: 53
                                line: 1
                              }
                              start: Object {
                                column: 52
                                index: 52
                                line: 1
                              }
                            }
                          }
                          typeParameters: undefined
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 53
                              index: 53
                              line: 1
                            }
                            start: Object {
                              column: 52
                              index: 52
                              line: 1
                            }
                          }
                        }
                      ]
                    }
                  }
                }
              }
              FlowFunctionTypeParam {
                name: Identifier {
                  name: 'cb'
                  loc: Object {
                    filename: 'input.js'
                    identifierName: 'cb'
                    end: Object {
                      column: 58
                      index: 58
                      line: 1
                    }
                    start: Object {
                      column: 56
                      index: 56
                      line: 1
                    }
                  }
                }
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 61
                    index: 61
                    line: 1
                  }
                  start: Object {
                    column: 56
                    index: 56
                    line: 1
                  }
                }
                meta: PatternMeta {
                  optional: false
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 61
                      index: 61
                      line: 1
                    }
                    start: Object {
                      column: 56
                      index: 56
                      line: 1
                    }
                  }
                  typeAnnotation: FlowGenericTypeAnnotation {
                    id: ReferenceIdentifier {
                      name: 'P'
                      loc: Object {
                        filename: 'input.js'
                        identifierName: 'P'
                        end: Object {
                          column: 61
                          index: 61
                          line: 1
                        }
                        start: Object {
                          column: 60
                          index: 60
                          line: 1
                        }
                      }
                    }
                    typeParameters: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 61
                        index: 61
                        line: 1
                      }
                      start: Object {
                        column: 60
                        index: 60
                        line: 1
                      }
                    }
                  }
                }
              }
            ]
          }
        }
      }
      predicate: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 86
          index: 86
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
    }
  ]
}
```
