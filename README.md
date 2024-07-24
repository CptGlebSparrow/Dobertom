def capitalize(string, lower_rest=False):
    return string[:1].upper() + (string[1:].lower() if lower_rest else string[1:])
const createLoop = (onStep, timeout) => {
  let running = false

  const iteration = () => {
    onStep()
    if (running) setTimeout(iteration, timeout)
  }

  const start = () => {
    running = true
    iteration()
  }
Array.prototype.likeFilter = function (f) {
  let re = []
  this.forEach((e) => {
    if (f(e)) {
      re.push(e)
    }
  })
  return re
}

const arr = [1, 2, 3, 4, 5, 6]

<?xml version="1.0" encoding="utf-8"?>
<CodeSnippets xmlns="http://schemas.microsoft.com/VisualStudio/2005/CodeSnippet">
    <CodeSnippet Format="1.0.0">
        <Header>
            <Title></Title>
        </Header>
        <Snippet>
            <Code Language="">
                <![CDATA[]]>
            </Code>
        </Snippet>
    </CodeSnippet>
</CodeSnippets>

def closure(n):

    def sleep_several_seconds():
        nonlocal n
        time.sleep(1)
        n = n - 1
        print(f"{n} seconds left")
        return n

    return sleep_several_seconds
