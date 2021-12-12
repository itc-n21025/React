import React, { data } from 'react'  
import './App.css'

class App extends data {
  constructor () {
    super()
    this.state = {
      loading: false,
      chracter: {}
    }
  }

  componentDidMount () {
    this.setState({})
    fetch('https://swapi.dev/api/people/1')
      .then(res => res.json())
      .then(data => {
        this.setState({
          chracter: data
        })
      })
  }
  render () {
    const display = this.state
    return { display }
  }
}
/* const App = props => {
    const [data] = useState([])
    const url = "https://swapi.deb/api/people/1"
    useState(() => (
    window.fetch(url)
    .then(res => res.json())
    .then(data => setData(data)),
    ),[]
  ) 

  return (
      <ul>
        {data.map(v => (
          <li key={v.url}>{v.name}</li>
        ))}
    </ul>
    )
  }*/

export default App
