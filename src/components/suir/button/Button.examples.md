## Generic

    const Button = require('semantic-ui-react').Button;
    <Button className=''>Test button</Button>

## Positive Button

    const Button = require('semantic-ui-react').Button;
    <div>
      <Button positive className=''>
        Positive
      </Button>
      <Button positive className=''>
        <i className='icon_check' style={{marginRight: '10px'}} />
        Positive with Icon
      </Button>
    </div>

## Negative Button

    const Button = require('semantic-ui-react').Button;
    <Button negative className=''>
    <i className='icon_close' style={{marginRight: '10px'}} />
    Negative
    </Button>

## Primary Button

    const Button = require('semantic-ui-react').Button;
    <div>
      <Button primary className=''>
        <i className='icon_check' style={{marginRight: '10px'}} />
        Primary
      </Button>
      <Button primary active className=''>
        <i className='icon_check' style={{marginRight: '10px'}} />
        Primary Active
      </Button>
      <Button primary disabled className=''>
        <i className='icon_check' style={{marginRight: '10px'}} />
        Primary Disabled
      </Button>
    </div>

## Secondary Button

    const Button = require('semantic-ui-react').Button;
    <div>
      <Button secondary className=''>
        <i className='icon_check' style={{marginRight: '10px'}} />
        Secondary
      </Button>
      <Button secondary active className=''>
        <i className='icon_check' style={{marginRight: '10px'}} />
        Secondary Active
      </Button>
      <Button secondary disabled className=''>
        <i className='icon_check' style={{marginRight: '10px'}} />
        Secondary Disabled
      </Button>
    </div>

## Disabled Button

    const Button = require('semantic-ui-react').Button;
    <Button className='' disabled >Some Copy </Button>

## Active Button

    const Button = require('semantic-ui-react').Button;
    <Button className='' active>
        Some Copy
    </Button>

## Icon Button

    const Button = require('semantic-ui-react').Button;
    <div>
      <div>
        <Button icon>
          <i className='icon_plus' style={{fontSize: '25px'}} />
        </Button>
        Normal
      </div>
      <div>
        <Button icon active>
          <i className='icon_plus' style={{fontSize: '25px'}} />
        </Button>
        Active
      </div>
      <div>
        <Button icon disabled>
          <i className='icon_plus' style={{fontSize: '25px'}} />
        </Button>
        Disabled
      </div>
    </div>

## Adjacent Buttons

    const Button = require('semantic-ui-react').Button;
    <div>
      <Button>Good Button</Button>
      <Button color='red'>Best Button</Button>
      <Button color='purple'>!! OMG FAVORITE Button !!</Button>
    </div>

See full input documentation [here](http://react.semantic-ui.com/elements/button)