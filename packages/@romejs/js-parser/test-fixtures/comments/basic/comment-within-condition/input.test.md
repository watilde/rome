# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `comments > basic > comment-within-condition`

```javascript
Program {
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
      index: 31
      line: 3
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  comments: Array [
    CommentBlock {
      id: '0'
      value: ' foo '
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 9
          index: 9
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
    }
    CommentBlock {
      id: '1'
      value: ' bar '
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 13
          index: 23
          line: 2
        }
        start: Object {
          column: 4
          index: 14
          line: 2
        }
      }
    }
  ]
  body: Array [
    IfStatement {
      alternate: undefined
      leadingComments: Array ['0']
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 20
          index: 30
          line: 2
        }
        start: Object {
          column: 0
          index: 10
          line: 2
        }
      }
      consequent: BlockStatement {
        body: Array []
        directives: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 20
            index: 30
            line: 2
          }
          start: Object {
            column: 18
            index: 28
            line: 2
          }
        }
      }
      test: ReferenceIdentifier {
        name: 'a'
        leadingComments: Array ['1']
        loc: Object {
          filename: 'input.js'
          identifierName: 'a'
          end: Object {
            column: 16
            index: 26
            line: 2
          }
          start: Object {
            column: 15
            index: 25
            line: 2
          }
        }
      }
    }
  ]
}
```
