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

