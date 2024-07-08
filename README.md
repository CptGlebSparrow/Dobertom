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

  const stop = () => {
    running = false
  }

  return { start, stop }
}

const mainLoop = createLoop(() => {
  console.log('test')
}, 100)
