# marko-intl-tel-input
International telephone number Markojs input component, build using [Intl-tel-input](http://intl-tel-input.com)

## Installation

`
npm install intl-tel-input --save
` 

or

`
yarn add intl-tel-input
`

## Usage

```marko

<IntlTelInput class="form-control"
              name="phone"
              value=state.phone
              placeholder="Phone Number"
              E123=true
              on-change("onHandleChange")
              on-error("onHandleError")/>

```

Feedback & Contribution
-------

You know the say: No one is whole alone! So, feedbacks are all welcome. Kindly report any encounted [Issues here][] and I'll be glad to work on it right away. Thank you.


License
-------

This software is free to use under the MIT license. See the [LICENSE file][] for license text and copyright information.


[LICENSE file]: https://github.com/fabrice8/marko-intl-tel-input/blob/master/LICENSE
[Issues here]: https://github.com/fabrice8/marko-intl-tel-input/issues