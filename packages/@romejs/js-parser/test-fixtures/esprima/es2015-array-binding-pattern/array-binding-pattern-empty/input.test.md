# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-array-binding-pattern > array-binding-pattern-empty`

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
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 9
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 8
          index: 8
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: ArrowFunctionExpression {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 7
            index: 7
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        body: NumericLiteral {
          value: 0
          format: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 7
              index: 7
              line: 1
            }
            start: Object {
              column: 6
              index: 6
              line: 1
            }
          }
        }
        head: FunctionHead {
          async: false
          hasHoistedVars: false
          predicate: undefined
          rest: undefined
          returnType: undefined
          thisType: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 6
              index: 6
              line: 1
            }
            start: Object {
              column: 0
              index: 0
              line: 1
            }
          }
          params: Array [
            BindingArrayPattern {
              elements: Array []
              rest: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 3
                  index: 3
                  line: 1
                }
                start: Object {
                  column: 1
                  index: 1
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
```
